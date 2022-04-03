<template>
  <div id="app" class="wrapper">
    <header>
      <h1>devfinder</h1>
      <p>DARK <i class="fa-solid fa-moon"></i></p>
    </header>
    <!-- <router-view /> -->
    <main>
      <SearchBar></SearchBar>
      <SearchResult></SearchResult>
    </main>
  </div>
</template>
<script>
import SearchBar from '@/components/SearchBar.vue';
import SearchResult from '@/components/SearchResult.vue';

export default {
  components: {
    SearchBar,
    SearchResult,
  },
};
</script>

<style lang="scss">
#app {
  font-family: 'Space Mono', monospace, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  background-color: #f6f8ff;
}
.wrapper {
  display: grid;
  grid-template-columns: 730px;
  justify-content: center;
}
header {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}
header h1 {
  margin: 144px 0 36px 0;
}
header p {
  height: 38px;
  margin: 144px 0 36px 0;
  font-size: 13px;
  font-weight: bold;
  color: #697c9c;
}
header p i {
  font-size: 20px;
}
main div {
  display: flex;
}
</style>
