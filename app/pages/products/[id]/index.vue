<script setup>
 
 const route = useRoute();

</script>


<template>
    <div class="mx-auto max-w-2xl">
        <h2 class="page-title mb-4">
            Product Detail Page
        </h2>
        <div class="card">
            <p class="text-slate-600">You are viewing the details for product ID: <span class="font-mono font-semibold text-slate-900">{{ route.params.id }}</span></p>
        </div>
        <NuxtLink to ="/products/about" class="btn btn-ghost mt-6">Go to Product's About</NuxtLink>
    </div>
</template>
