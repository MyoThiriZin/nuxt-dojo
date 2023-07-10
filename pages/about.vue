<template>
    <div>
        <p>Hello This is about page</p>
    </div>
    <div>
        {{ data }}
    </div>
</template>

<script setup>
    // const { data } = await useFetch('/api/api?name=MTZ',{
    //     method: 'post',
    //     body: { age: 24 }
    // })
    const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>

</style>