<template>
  <main>
    <div class="bg_dark">
      <div class="content_contain">
      <div class="contain d-flex align-items-center h-100">
        <h2 class="">--&gt; CONTENT GOES HERE &LT;--</h2>
      </div>
      </div>
    </div>

    <div class="bg_primary">
      <div class="cards_contain contain d-flex">
      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <p class="card_text">DIGITAL COMICS</p>
      </div>

      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-comics-merchandise.png" alt="" />
        <p class="card_text">DC MERCHANDISE</p>
      </div>

      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
        <p class="card_text">SUBSCRIPTION</p>
      </div>

      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
        <p class="card_text">COMIC SHOP LOCATOR</p>
      </div>

      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
        <p class="card_text">DC POWER VISA</p>
      </div>
    </div>
    </div>
  </main>
</template>

<script>
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