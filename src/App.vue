<template>
  <div id="app">
    <div class="contain">
      <SiteHeader />
      <!-- Site Header -->
    </div>

      <SiteMain />
      <!-- Site main -->

      <SiteFooter/>
  </div>
</template>

<script>
import SiteHeader from "./components/header.vue";

import SiteMain from "./components/main.vue";

import SiteFooter from "./components/footer.vue";


export default {
  name: "app",
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter
  },
};
</script>

<style lang="scss">
@import './assets/scss/variables.scss';
@import './assets/scss/common.scss';


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Kalam", cursive;
  font-family: "Montserrat", sans-serif;
}
</style>
