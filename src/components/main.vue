<template>
  <main>
    <Jumbo />

    <div class="bg_dark">
      <div class="content_contain">
      <div class="contain d-flex align-items-center h-100">
        <h2 class="">--&gt; CONTENT GOES HERE &LT;--</h2>
      </div>
      </div>
    </div>

    <Cards />
  </main>
</template>

<script>
import Cards from './cards.vue'

import Jumbo from './jumbo.vue'

export default {
  components: {
    Cards,
    Jumbo
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
    height: 200px;
  }
}
</style>