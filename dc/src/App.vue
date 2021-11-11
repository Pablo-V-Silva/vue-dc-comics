<template>
  <div id="app">
    <SiteHeader />
  </div>
</template>

<script>

import SiteHeader from './components/header.vue'

export default {
  name: 'app',
  components: {
    SiteHeader
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Kalam", cursive;
  font-family: "Montserrat", sans-serif;
}


</style>
