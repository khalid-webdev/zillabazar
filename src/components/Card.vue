<script setup>
import { defineProps } from "vue";
import { useRouter } from "vue-router";
const router = useRouter();
const { product } = defineProps(["product"]);
console.log(product);
const addToCart = (cartNumber,price) => {
};
</script>

<template>
	<div class="prod_card">
    <div class="image">
      <img class="productImage" :src="product.image" alt="product image" />
    </div>
		<div class="prod_card_info">
      <div>
			<h1 class="prod_title"> {{product.title.slice(0,20)}}...</h1>
      <div class="prod_price flex">
        <h3>Tk: 990.00</h3>
        <h3 class="discount">Tk 1200.00</h3>
      </div>
			<div class="flex">
        <div class="rating">
				<span><i class="bx bxs-star" style="color: #feff00"></i></span>
				<span><i class="bx bxs-star" style="color: #feff00"></i></span>
				<span><i class="bx bxs-star" style="color: #feff00"></i></span>
				<span><i class="bx bxs-star" style="color: #feff00"></i></span>
				<span><i class="bx bxs-star-half" style="color: #feff00"></i></span>
			</div>
      <h2>4.6</h2>
      </div>
		</div>
  </div>
    <div class="cart flex justify_center">
      <button @click="addToCart" class="btn primary">Add to Cart</button>
    </div>

	</div>
</template>

<style scoped>
.prod_card {
	border: 1px solid var(--light);
	padding: 0.8rem;
	border-radius: 2rem;
  background: var(--light);
	cursor: pointer;
	transition: all 350ms ease;
}
.image{
   overflow: hidden;
}

.prod_card:hover {
	box-shadow: 10px 5px 10px var(--background);

}
h2{
  margin-left: 1rem;
  color: var(--paragraph);
}
.prod_card img {
width: 100%;
	border-radius: 2rem;
	margin: 0 0 1.5rem;
	transition: all 350ms ease;
  	border-radius: 2rem;

}
.prod_card .image:hover img {
	transform: scale(1.1);
  	border-radius: 2rem;
}
.prod_card_info {
	padding: 0 0.5rem;
}
.prod_title{
  transition:all .25s ease ;
  font-family: "Poppins",sans-serif;
  font-size: 1.8rem;
  font-weight: normal;
  color: var(--secondary);
}
.prod_title:hover{
color: #727272;
}
.prod_card_info h4 {
	color: #ababab;
	font-size: 1.1rem;
	margin: 0;
	padding: 0;
}

.prod_card_info h3 {
	font-size: 1.5rem;
	margin: 0.7rem 0;
	font-family: "raleway_semibold";
	cursor: default;
}

.rating {
	display: inline-flex;
	align-items: center;
  margin-bottom: 1rem;
}
.rating span {
	font-size: 1.5rem;
}

.prod_price{
  margin: 1rem 0;
}
.prod_price h3 {
	font-size: 2rem;
	color: #4f4f4f;
  font-weight: 600;
  margin-right: 1.5rem;
}
.prod_price .discount{
  font-style: italic;
  font-weight: normal;
  text-decoration: line-through;
}
.prod_card_info {
	position: relative;
}
.cart button.btn.primary{
  font-size: 1.7rem;
  width: 100%;
  margin-bottom: .7rem;
}
.cart button.btn.primary:hover{
  color: var(--primary);
}
</style>
