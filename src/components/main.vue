<template>
  <main>
    <Jumbo />

    <div class="bg_dark">
      <div class="content_contain">
      <div class="contain d-flex align-items-center h-100">
        <Products />
      </div>
      </div>
    </div>

    <Cards />
  </main>
</template>

<script>
import Cards from './cards.vue'

import Jumbo from './jumbo.vue'

import Products from './products.vue'

export default {
  components: {
    Cards,
    Jumbo,
    Products
  }
}
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
@import "../assets/scss/common.scss";

main {
  .bg_dark {
    background-color: $secondary_color;
  }
  .content_contain {
    color: $fourth_color;
    padding: 2rem 0;
  }
}
</style>