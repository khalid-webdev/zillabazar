<script setup>
import 'vue3-carousel/carousel.css'
import { Carousel, Slide, Navigation } from 'vue3-carousel'
import { ref } from 'vue'
const images = ref([
  {
    id: 1,
    imageUrl:"./src/assets/banner/hero2.jpeg"
  },
  {
    id: 2,
    imageUrl:"./src/assets/banner/hero1.png"
  },
  {
    id: 3,
    imageUrl:"./src/assets/banner/hero.png"
  }
])

const config = {
  height: 620,
  itemsToShow: 1,
  autoplay: 2500,
  gap:4,
  wrapAround: true,
  pauseAutoplayOnHover: true,
}
</script>

<template>
  <div class="hero_section">
    <Carousel v-bind="config">
    <Slide v-for="image in images" :key="image.id">
      <img :src="image.imageUrl" alt="image" />
    </Slide>
  </Carousel>
    <div class="container">
      <h1>Shop Smart. Live Better.</h1>
      <p>Discover handpicked products at prices you’ll love <br> — delivered straight to your door.</p>
      <button class="btn primary">Shop now</button>
      <button class="btn common">Explore Collections...<i class='bx bxs-right-top-arrow-circle' ></i></button>
    </div>
  </div>
</template>

<style scoped>
/* .hero_section{
  width: 100%;
  height: 600px;
  background-image: url('../assets/banner/hero2.jpeg');
  background-size: cover;
  position: relative;
  display: inline-block;
}
*/
.hero_section{
  width: 100%;
  height: 620px;
  position: relative;
  display: inline-block;
}
.hero_section img{
  width: 100%;
  height: inherit;
  object-fit: cover;
}
.hero_section::after {
  content: ""; /* Required for pseudo-elements */
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0; /* Makes the pseudo-element cover the entire container */
  background-image: linear-gradient(to bottom, rgba(0, 0, 0, .5), rgba(0, 0, 0, .1));
  z-index: 1; /* Ensures the gradient is on top of the image */
}
.container{
  position: absolute;
  top: 25%;
  left: 10%;
  z-index: 3;
}
.container h1{
  font-size: 7rem;
  color: var(--light);
}
.container p{
  font-size: 1.8rem;
  margin: 1rem 0;
  color: #dfdfdf;
  font-family: "Poppins",sans-serif;
  font-style: italic;
}

button.btn.common{
  margin-top: 2rem;
  border-radius: 20px;
  padding: 1rem 2rem;
  background: none;
  border: 1px solid transparent;
  color: var(--primary);
  font-size: 2rem;
  font-weight: bold;
}
button.btn.primary{
  margin-right: 2.5rem;
  border-radius: 20px;
  padding: 1rem 2.5rem;
  background: var(--primary);;
  color: var(--light);
  font-size: 1.72rem;
  font-family: "Raleway",sans-serif;
  font-weight: bold;
}
.btn:hover{
  background: transparent!important;
  border: .5px solid var(--primary)!important;
}
</style>
