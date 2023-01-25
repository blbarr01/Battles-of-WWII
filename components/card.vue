<template>
    <div class="border-2 border-black">
        <img :src="`${img}`" />
        <h2 class="mx-auto text-5xl text-regal-blue">{{ title }}</h2>
        <p class="">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur suscipit cum accusantium, voluptas
            asperiores temporibus hic sed commodi, odio doloribus cupiditate. Tempore, facilis deserunt!</p>
    </div>
</template>

<script setup>
defineProps(['title', 'img']);
</script>

<style scoped>

</style>