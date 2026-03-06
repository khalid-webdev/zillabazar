<script setup>
import { RouterView } from 'vue-router';
import Nav from './components/Nav.vue'
import ContactBanner from './components/ContactBanner.vue'
import Footer from '@/components/Footer.vue';
</script>

<template>
  <main>
    <ContactBanner/>
    <Nav/>
    <RouterView/>
    <Footer/>
  </main>
</template>

<style scoped>
.spacer{
  height: 50vh;
}
</style>
