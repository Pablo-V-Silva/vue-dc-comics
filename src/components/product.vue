<template>
<div class="card">
  <div class="thumb">
    <img :src="thumb" alt="">
    <p class="py-1">{{ series.toUpperCase() }}</p>
  </div>
</div>
  
</template>

<script>
export default {
  props: {
    thumb: String,
    series: String
  }
}
</script>

<style>

</style>