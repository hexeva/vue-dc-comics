<template>
  <div id="app">
    <div>
      <Header />

      <main>
        <div class="main-jumbotron"></div>
        <MainProducts />

      </main>


          <Section />


      <Footer />

    </div>

    
    
    
  </div>
</template>

<script>

import Header from "./components/Header.vue";
import Section from "./components/Section.vue";
import Footer from "./components/Footer.vue";
import MainProducts from "./components/MainProducts.vue"
;

export default {
  name: "App",
  components: {
    Header,
    Section,
    MainProducts,
    Footer,
    
  },
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';
@import './style/mixins.scss';

// MAIN


.main-jumbotron{
  width: 100%;
  height: 385px;
  background-image: url(../src/assets/img/jumbotron.jpg);
  @include background_general;

}





  

</style>
