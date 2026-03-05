<script setup>

</script>

<template>
  <div class="topbanner">
    <div class="container flex item_center justify_between">
      <div class="social_icon flex item_center">
        <i class='bx bxl-facebook'></i>
        <i class='bx bxl-twitter' ></i>
        <i class='bx bxl-instagram-alt' ></i>
      </div>
      <div class="right">
        <h4>Call us: 01789123425</h4>
      </div>
    </div>
  </div>
</template>

<style scoped>
.topbanner{
  background: #000;
  color: white;
}
.container{
  padding: 0 2rem;
}
.social_icon{
  gap: .5rem;
  font-size: 1.2rem;
  padding: .5rem 0;
  cursor: pointer;
}
.right h4{
  font-style: italic;
  font-size: 1.2rem;
}
</style>
