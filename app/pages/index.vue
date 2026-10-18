<template>
  <div class="text-center">
    <h2 class="text-4xl font-bold tracking-tight text-blue-800 underline decoration-blue-300 decoration-2 underline-offset-8 sm:text-5xl">Home Page</h2>
    <!-- Nuxt Link  -->
    <div class="mt-10 flex flex-col items-center justify-center gap-4 sm:flex-row">
      <NuxtLink to="/contact" class="btn btn-primary">Contact</NuxtLink>
      <NuxtLink to="/products" class="btn btn-ghost">Products</NuxtLink>
      <NuxtLink to = "/blogs" class="btn btn-ghost">Blogs</NuxtLink>
    </div>
  </div>
</template>
