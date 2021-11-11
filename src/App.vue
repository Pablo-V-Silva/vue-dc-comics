<template>
  <div id="app">
    <div class="contain">
      <SiteHeader />
    </div>
  </div>
</template>

<script>
import SiteHeader from "./components/header.vue";

export default {
  name: "app",
  components: {
    SiteHeader,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Kalam", cursive;
  font-family: "Montserrat", sans-serif;
}

.contain {
  width: 1200px;
  margin: auto;
}
</style>
