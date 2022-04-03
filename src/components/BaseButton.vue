<template>
  <div>
    <button><slot>Search</slot></button>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
button {
  height: 50px;
  width: 106px;
  background: #0079ff;
  border: none;
  border-radius: 10px;
  color: white;
  font-family: 'Space Mono', monospace, sans-serif;
  font-size: 16px;
  font-weight: bold;
}
</style>
