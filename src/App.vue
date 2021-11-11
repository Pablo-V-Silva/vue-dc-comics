<template>
  <div id="app">
    <div class="contain">
      <SiteHeader />
      <!-- Site Header -->
    </div>


    <div class="bg_dark">
      <div class="contain">
      <SiteMain />
      <!-- Site main -->
      </div>
    </div>
  </div>
</template>

<script>
import SiteHeader from "./components/header.vue";

import SiteMain from "./components/main.vue";


export default {
  name: "app",
  components: {
    SiteHeader,
    SiteMain
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

.bg_dark {
  background-color: $secondary_color;
}
</style>
