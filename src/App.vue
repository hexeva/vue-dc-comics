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
// *{
//   margin: 0;
//   padding: 0;
//   box-sizing: border-box;
// }
// img{
//   width: 100%;
// }
// .container{
//   width: 70%;
//   margin: auto;
//   height:100%;
//   /* test */
//   background-color: antiquewhite;
// }
  

</style>
