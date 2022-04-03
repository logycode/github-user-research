<template>
  <div class="home">
    <search-bar />
  </div>
</template>

<script>
// @ is an alias to /src
import SearchBar from '@/components/SearchBar.vue';

export default {
  name: 'HomeView',
  components: {
    SearchBar,
  },
};
</script>
