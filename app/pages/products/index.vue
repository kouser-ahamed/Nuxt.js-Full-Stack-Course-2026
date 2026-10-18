<template>
  <div>
    <h2 class="page-title mb-8">Product Home Page</h2>
    <div class="grid gap-4 sm:grid-cols-2 lg:grid-cols-3">
      <NuxtLink to="/products/about" class="card block font-semibold text-slate-900 transition hover:-translate-y-0.5 hover:border-slate-300 hover:shadow-md"> Go to Product's About </NuxtLink>

      <NuxtLink to="/products/1" class="card block font-semibold text-slate-900 transition hover:-translate-y-0.5 hover:border-slate-300 hover:shadow-md"> Daynamic Product 1 </NuxtLink>
      <NuxtLink to="/products/2" class="card block font-semibold text-slate-900 transition hover:-translate-y-0.5 hover:border-slate-300 hover:shadow-md"> Daynamic Product 2 </NuxtLink>
      <NuxtLink to="/products/3" class="card block font-semibold text-slate-900 transition hover:-translate-y-0.5 hover:border-slate-300 hover:shadow-md"> Daynamic Product 3 </NuxtLink>
      <NuxtLink to="/products/4" class="card block font-semibold text-slate-900 transition hover:-translate-y-0.5 hover:border-slate-300 hover:shadow-md"> Daynamic Product 4 </NuxtLink>
    </div>
  </div>
</template>
