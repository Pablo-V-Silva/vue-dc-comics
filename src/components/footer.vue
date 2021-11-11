<template>
  <footer>
    <div class="footer_jumbo">
      <div class="contain d-flex">
        <div class="links col-6 d-flex py-3">
          <div class="col-4">
            <div class="part">
              <h3 class="py-1">DC COMICS</h3>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quibusdam!</a></li>
                <li><a href="">Recusandae!</a></li>
                <li><a href="">Ratione?</a></li>
                <li><a href="">Sunt.</a></li>
                <li><a href="">Suscipit!</a></li>
                <li><a href="">Sit!</a></li>
              </ul>
            </div>

            <div class="part">
              <h3 class="py-1">SHOP</h3>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quibusdam!</a></li>
              </ul>
            </div>
          </div>
          <div class="col-4">
            <div class="part">
              <h3 class="py-1">DC</h3>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quibusdam!</a></li>
                <li><a href="">Recusandae!</a></li>
                <li><a href="">Ratione?</a></li>
                <li><a href="">Sunt.</a></li>
                <li><a href="">Suscipit!</a></li>
                <li><a href="">Sit!</a></li>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quibusdam!</a></li>
                <li><a href="">Recusandae!</a></li>
                <li><a href="">Ratione?</a></li>
                <li><a href="">Sunt.</a></li>
              </ul>
            </div>
          </div>
          <div class="col-4">
            <div class="part">
              <h3 class="py-1">SITES</h3>
              <ul>
                <li><a href="">Lorem.</a></li>
                <li><a href="">Quibusdam!</a></li>
                <li><a href="">Recusandae!</a></li>
                <li><a href="">Ratione?</a></li>
                <li><a href="">Sunt.</a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-6 dc_logo_footer"></div>
      </div>
    </div>
    <div class="credits">
      <div class="contain d-flex jc-between align-items-center">
        <button>SIGN-UP NOW!</button>
        <div class="social-contain d-flex">
          <p class="px-1">FOLLOW US</p>
          <div class="socials-icons">
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
            <img src="../assets/img/footer-periscope.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
</script>

<style lang="scss">
@import '../assets/scss/variables.scss';

footer {
  background-image: url('../assets/img/footer-bg.jpg');
  background-repeat: no-repeat;
  background-size: cover;

  h3 {
    font-size: 1.5rem;
    color: $fourth_color;
  }
  ul {
    list-style: none;
    li {
      padding: 0.25rem 0;
    }

    a {
      text-decoration: none;
      color: $third_color;
    }
  }

  .dc_logo_footer {
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }

  .credits {
    background-color: $fifth_color;
  }

  button {
    padding: 1.5rem 1.7rem;
    font-size: 1.5rem;
    font-weight: 600;
    background-color: $fifth_color;
    color: $fourth_color;
    border: 2px solid $principal_color;
    margin: 1.2rem 0;

    &:hover {
      background-color: $principal_color;
      cursor: pointer;
    }
  }

  .social-contain {
    p {
      color: $principal_color;
      font-weight: bold;
      font-size: 1.5rem;
    }

    img {
      margin: 0 0.5rem;

      &:hover {
        cursor: pointer;
      }
    }
  }
}
</style>