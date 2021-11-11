<template>
  <header class="d-flex jc-between align-items-center">
    <div class="logo_contain">
      <img src="../assets/img/dc-logo.png" alt="" />
    </div>

    <nav>
      <ul class="d-flex">
        <li><a href="">CHARACTER</a></li>
        <li><a href="">COMICS</a></li>
        <li><a href="">MOVIES</a></li>
        <li><a href="">TV</a></li>
        <li><a href="">GAMES</a></li>
        <li><a href="">COLLECTIBLES</a></li>
        <li><a href="">VIDEOS</a></li>
        <li><a href="">FANS</a></li>
        <li><a href="">NEWS</a></li>
        <li><a href="">SHOP</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
</script>

<style lang="scss">
.d-flex {
  display: flex;
}

.jc-between {
  justify-content: space-between;
}

.align-items-center {
  align-items: center;
}

header {
  ul {
    li {
      list-style: none;
      margin-left: 1rem;
      font-weight: 600;
      border: 10px solid transparent;

      &:hover {
        border-bottom: 10px solid blue;
      }

      a { 
        line-height: 107px;
        text-decoration: none;
        color: black;

        &:hover {
          color: blue;
        }
      }
    }
  }
}
</style>