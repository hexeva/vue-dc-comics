<template>
  <div id="app">
    <div>
      <Header />

      <main>
        <div class="container">
          CONTENT GOES HERE
        </div>
      </main>
      <Section />

    </div>

    
    
    
  </div>
</template>

<script>

import Header from "./components/Header.vue";
import Section from "./components/Section.vue";

export default {
  name: "App",
  components: {
    Header,
    Section,
    
  },
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';





  

</style>
