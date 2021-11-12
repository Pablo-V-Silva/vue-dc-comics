<template>
  <div class="jumbo">
    <div class="contain">
      <div class="currentSeries">CURRECT SERIES</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import '../assets/scss/variables.scss';

.jumbo {
  height: 500px;
  background-image: url('../assets/img/jumbotron.jpg');
  position: relative;
}

.currentSeries {
  width: fit-content;
  padding: 1.1rem 1.5rem;
  background-color: $principal_color;
  font-size: 1.5rem;
  font-weight: 500;
  position: absolute;
  bottom: -30px;
}
</style>