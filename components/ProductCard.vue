<template>
    <div class="cards text-center">
        <img :src="product.image" :alt="product.title" class="cart-img">
        <p class="font-bold text-gray-500 m-4 truncate">{{ product.title }}</p>
        <NuxtLink :to="`/product/${product.id}`">
        <p class="btn my-4">View Detail</p></NuxtLink>
    </div>
</template>

<script setup>
    const {product}=defineProps(['product'])
</script>

<style scoped>
    .cart-img {
        max-width: 70%;
        height: 120px;
        margin: 0 auto;
    }
</style>