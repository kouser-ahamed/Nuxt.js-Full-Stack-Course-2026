<script setup>
const route = useRoute();
</script>



<template>
  <div class="mx-auto max-w-2xl">
    <h2 class="mb-6 text-3xl font-bold tracking-tight text-rose-700 sm:text-4xl">Opps! Page Not found!</h2>

    <div class="card mb-6">
      <p class="text-slate-600">
        You Tried to access: <strong class="font-semibold text-slate-900"> {{ route.params.slug.join("/") }}</strong>
      </p>
    </div>

    <NuxtLink to="/blogs" class="btn btn-ghost">Go to Blogs Home</NuxtLink>
  </div>
</template>
