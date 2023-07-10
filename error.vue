<template>
    <div>
        <h2 class="font-bold text-center text-7xl mt-7">{{error.statusCode}}</h2>
        <p class="text-center mt-7">{{error.message}}</p>
    </div>
</template>

<script setup>
    defineProps(['error'])
</script>

<style scoped>

</style>