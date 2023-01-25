<template>
    <div>
        <header class="bg-neutral-800 py-12">
            <NuxtLink to="/">
                <h1 class="text-center text-8xl  text-white">Battles of WWII</h1>
            </NuxtLink>
            <nav class="container mx-auto mt-12">
            <ul class="flex justify-around p-3">
                <li class="text-white text-4xl border-white border-4 p-4"><NuxtLink to="/">Home</NuxtLink></li>
                <li class="text-white text-4xl border-white border-4 p-4"><NuxtLink to="/about">About</NuxtLink></li>
                <li class="text-white text-4xl border-white border-4 p-4"><NuxtLink to="/battles">Battles Index</NuxtLink></li>
            </ul>
        </nav>
        </header>

        <div class="container mx-auto mt-24 border-2 border-black p-12">
            <slot /> 
        </div>
    </div>
</template>

<script>

</script>

<style  scoped >
    header{
        border: 2px solid black;
    }
</style>