
<script setup>
import Card from '@/components/Card.vue';
import products from '../data/products.json'
</script>

<template>
  <div class="products">
<div class="container">
  <div class="section_heading">
    <h1>All Products</h1>
    <p>Find It. Love It. Own It.</p>
  </div>
  <div class="products">
    <div class="products_container">
      <Card v-for="(product,index) in products" :key="index" :product="product"/>
    </div>
  </div>
</div>
  </div>
</template>

<style scoped>
.products{
  background: var(--background);
  padding: 4rem 0;
}

.products_container{
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
	gap: 3rem!important;
}

</style>
