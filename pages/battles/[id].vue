<template>
    <div>
        <h2>battle name</h2>
        <p>{{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam quaerat in deserunt temporibus, numquam
            eligendi voluptas fugiat sed dolore commodi modi rerum eum tenetur.</p>
    </div>
</template>

<script setup>
const route = useRoute()
let id = route.params.id; 
console.log(route.params);
const uri = `https://en.wikipedia.org/w/api.php?action=query
&prop=extracts
&exsentences=2
&exlimit=1
&titles=${id}
&explaintext=1
&format=json
&formatversion=2
&origin=*
`;


const {data: page} = await useFetch(uri);
console.log('page:');
console.log(page);


</script>

<style lang="scss" scoped>

</style>

