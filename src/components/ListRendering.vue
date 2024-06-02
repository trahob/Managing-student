<template>
	<div class="list-rendering" >
        <tr v-for="(food, index) in foods" :key="index">
            <td>{{ food.name }}</td>
            <td>{{ food.price }}</td>
            <td>{{ food.currency }}</td>
          </tr>
	</div>
</template>

<script>
    export default {
        data() {
            return {
                foods: [
                    { name: 'Product 1', price: 10, currency: 'USD' },
                    { name: 'Product 2', price: 20, currency: 'USD' },
                    { name: 'Product 3', price: 15, currency: 'USD' },
                    { name: 'Product 4', price: 25, currency: 'USD' }
                ]
            }
        }
    }
</script>

<style scoped>
</style>