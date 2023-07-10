<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="logo font-bold">NUXT-DOJO</NuxtLink>
                <ul class="flex justify-between">
                    <li><NuxtLink to="/" class="p-4">home</NuxtLink></li>
                    <li><NuxtLink to="/about" class="p-4">about</NuxtLink></li>
                    <li><NuxtLink to="/product" class="p-4 btn">product</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- output the page content -->
        <div class="container mx-auto p-4">
           <slot/>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.router-link-active {
    font-weight: bold;
}
.logo {
    color: #00ffff;
}
</style>