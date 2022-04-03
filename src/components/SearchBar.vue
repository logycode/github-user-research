<template>
  <div>
    <div class="search-bar">
      <div>
        <label for="search">
          <font-awesome-icon
            icon="fa-solid fa-magnifying-glass"
            class="mag-glass"
          />
        </label>
        <input
          type="text"
          name="search"
          placeholder="Search GitHub username…"
        />
      </div>
      <BaseButton></BaseButton>
    </div>
  </div>
</template>
<script>
export default {
  name: 'SearchBar',
};
</script>
<style lang="scss" scoped>
.search-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  height: 69px;
  padding: 0 9.5px;
  background: white;
  border: none;
  border-radius: 15px;
  box-shadow: 0px 16px 30px -10px rgba(70, 96, 187, 0.2); /* offset-x | offset-y | blur-radius | spread-radius | color */
}
label {
  margin-left: 32px;
  margin-right: 24px;
  font-size: 24px;
}
input {
  width: 254px;
  height: 25px;
  padding: 8px;
  border: none;
  font-size: 13px;
  font-family: 'Space Mono', monospace, sans-serif;
  color: #4b6a9b;
}
input::placeholder {
  color: #4b6a9b;
  font-size: 18px;
}

.mag-glass {
  color: #0079ff;
}
</style>
