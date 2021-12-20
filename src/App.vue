<template>
  <div id="app">
    <div class="container">
      <Header />

      <main>Qui ci sarà il main</main>
    </div>
    
    
    
  </div>
</template>

<script>

import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
    
  },
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';



  

</style>
