<template>
  <main>
    <Jumbo />

    <div class="bg_dark">
      <div class="content_contain">
        <div class="contain mb-2 d-flex align-items-center h-100">
          <Products />
        </div>

        <div class="contain p-relative">
          <button class="btn">LOAD MORE</button>
        </div>
      </div>
    </div>

    <Cards />
  </main>
</template>

<script>
import Cards from "./cards.vue";

import Jumbo from "./jumbo.vue";

import Products from "./products.vue";

export default {
  components: {
    Cards,
    Jumbo,
    Products,
  },
};
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

  button.btn {
    position: absolute;
    left: 50%;
    bottom: 0px;
    transform: translate(-50%, 15px);
    width: fit-content;
    padding: 1.1rem 1.5rem;
    background-color: #0282F9;
    font-size: 1.5rem;
    font-weight: 500;
    border: 0;
    color: $fourth_color;

    &:hover {
      cursor: pointer;
    }
}
}
</style>