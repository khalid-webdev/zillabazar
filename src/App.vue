<script setup>
import { RouterView } from 'vue-router';
import Nav from './components/Nav.vue'
import ContactBanner from './components/ContactBanner.vue'
</script>

<template>
  <main>
    <ContactBanner/>
    <Nav/>
    <RouterView/>
    <div class="spacer"></div>
  </main>
</template>

<style scoped>
.spacer{
  height: 50vh;
}
</style>
