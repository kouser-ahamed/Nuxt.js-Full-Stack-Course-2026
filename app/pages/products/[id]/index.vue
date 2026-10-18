<script setup>
 
 const route = useRoute();

</script>


<template>
    <div>
        <h2>
            Product Detail Page
        </h2>
        <p>You are viewing the details for product ID: {{ route.params.id }}</p>
        <NuxtLink to ="/products/about">Go to Product's About</NuxtLink>
    </div>
</template>