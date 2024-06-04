<template>
	<div class="list-rendering" >
         <div class="product" v-for="(food, index) in foods" :key="index">
            <div>{{ food.name }}</div>
            <div>{{ food.price }}</div>
            <div>{{ food.currency }}</div>
            <img :src="food.src">
         </div>
         
	</div>
</template>

<script setup>
             const   foods= [
                    { name: 'Product 1', price: 30, currency: 'USD' , src:'/9.png'},
                    { name: 'Product 2', price: 20, currency: 'USD', src:'/9.png' },
                    { name: 'Product 3', price: 15, currency: 'USD',src:'/9.png' },
                    { name: 'Product 4', price: 25, currency: 'USD',src:'/9.png' }
             ]
</script>

<style scoped>
.product{
    display: flex;
    flex-direction: row;
}
</style>