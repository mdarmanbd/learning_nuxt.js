<script setup>


</script>

<template>
    <header>
        <nav>
            <ul>
                <li><NuxtLink to="/products">Products home page</NuxtLink></li>
               
            </ul>
       
        </nav>
    </header>
    <!---output the page content -->
    <div class="">
       <slot/>
    </div>
    <div class="">
        <ul>
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/Products">Products</NuxtLink></li>
            <li><NuxtLink to="/Products/1">Products id</NuxtLink></li>
        </ul>
    </div>
  
</template>

<style scoped>
.router-link-exact-active{
    color : 'yellow'
}
</style>