<template>
  <main>
    <div class="content_contain">
      <div class="contain d-flex align-items-center h-100">
        <h2 class="">--&gt; CONTENT GOES HERE &LT;--</h2>
      </div>
    </div>

    <div class="cards_contain d-flex">
      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <p class="card_text">DIGITAL COMICS</p>
      </div>

      <div class="card d-flex align-items-center">
        <img src="../assets/img/buy-comics-merchandise.png" alt="" />
        <p class="card_text">DC MERCHANDISE</p>
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
  .content_contain {
    color: $fourth_color;
    height: 200px;
  }

  .cards_contain {
    .card {
      padding: 1rem;

      img {
        width: 50px;
      }
      .card_text {
        padding-left: 0.5rem;
        color: $fourth_color;
      }
    }
  }
}
</style>