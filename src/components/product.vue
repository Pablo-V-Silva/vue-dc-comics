<template>
<div class="card">
  <div class="thumb">
    <img :src="thumb" alt="">
  </div>
</div>
  
</template>

<script>
export default {
  props: {
    thumb: String
  }
}
</script>

<style>

</style>