<script setup>
import { ref } from 'vue';
import {useRoute,useRouter} from 'vue-router'
const nav = ref(true);
const router = useRouter();

</script>

<template>
  <div class="navigation">
    <div class="container">
      <div class="logo flex item_center">
        <img @click="router.push('/')" src="../assets/images/zillabazar_logo.png" alt="">
        <div class="search_box">
          <input type="text" placeholder="Search...">
          <button class="btn"><i class='bx bx-search' ></i></button>
        </div>
      </div>
      <nav>
        <ul v-if="nav">
          <li><RouterLink to="/user" active-class="active"><i class='bx bxs-user-plus' ></i> Register</RouterLink></li>
          <li><RouterLink to="/user/login" active-class="active"><i class='bx bxs-user' ></i> Login</RouterLink></li>
          <li class="cart"><RouterLink to="/cart" active-class="active"><i class='bx bxs-cart-alt'></i><sup>5</sup></RouterLink></li>

        </ul>
        <ul v-else>
          <li><router-link to="/">hello</router-link></li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<style scoped>
.navigation{
  background:var(--background);
  padding: 0;
}
.container{
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo{
  width: 100px;
  cursor: pointer;
  height: 70px;
}
.logo img{
  width: 100%;
  margin-right: 1.2rem;
  object-fit: cover;
}
.search_box {
  display: flex;
  align-items: center;
  background: whitesmoke;
  width: 300px;
  height: 35px;
  border-radius: 20px;
  position: relative;
}
.search_box input{
margin-right: 2rem;
height: 100%;
border: 0;
padding:0 .7rem;
background: transparent;
outline: 0;
}
.search_box button {
height: 100%;
position: absolute;
right: 0;
background: transparent;
}
.search_box button i{
  font-size: 1.5rem;
}
nav ul{
  display: flex;
  align-items: center;
}
nav ul li{
  margin-left: 2rem;
}
nav ul li a {
  font-size: 1.5rem;
  font-family: "Raleway",sans-serif;
  color: var(--primary);
  font-weight: 600;
}
nav ul li.cart a{
  font-size: 2.3rem;
}
</style>
