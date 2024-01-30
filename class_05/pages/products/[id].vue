<script setup>
const {id} = useRoute().params
// link the page in layout products.vue page
definePageMeta({
    layout: 'products'
})

</script>

<template>

    <h3> id : {{ id }}</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque odit dignissimos assumenda soluta, debitis eligendi doloribus repudiandae placeat obcaecati corporis quibusdam sed culpa reiciendis tenetur impedit. Quo temporibus tenetur rerum.</p>
</template>