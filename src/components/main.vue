<template>
  <main>
    <div class="bg_dark">
      <div class="content_contain">
      <div class="contain d-flex align-items-center h-100">
        <h2 class="">--&gt; CONTENT GOES HERE &LT;--</h2>
      </div>
      </div>
    </div>

    <cards/>
  </main>
</template>

<script>
import cards from './cards.vue'

export default {
  components: {
    cards
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
  .bg_primary {
    background-color: $principal_color;
    padding: 5rem 0;
  }

  .cards_contain {
    .card {
      padding: 0.5rem;
      width: calc(100% / 5);

      img {
        height: 50px;
      }
      .card_text {
        padding-left: 0.5rem;
        color: $fourth_color;
      }
    }
  }
}
</style>