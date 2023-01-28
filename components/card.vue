<template>
    <div class="p-2 rounded-3xl shadow-md">
        <img class="mt-2" :src="`${img}`" />
        <h2 class="mx-auto md:text-2xl lg:text-3xl 2xl:text-5xl  text-center">{{ title }}</h2>
        <p class="">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur suscipit cum accusantium, voluptas
            asperiores temporibus hic sed commodi, odio doloribus cupiditate. Tempore, facilis deserunt!</p>
    </div>
</template>

<script setup>
defineProps(['title', 'img']);
</script>

<style scoped>

</style>