<template>
  <div class="flex min-h-screen flex-col">
    <header class="border-b border-slate-800 bg-slate-900 shadow-sm">
      <div class="mx-auto flex w-full max-w-6xl flex-wrap items-center justify-between gap-x-6 gap-y-2 px-4 py-4 sm:px-6">
        <h2 class="text-lg font-semibold tracking-wide text-white">Admin Dashboard</h2>
        <nav class="flex items-center gap-4">
          <NuxtLink to="/admin" class="nav-link">Dashboard</NuxtLink>
          <NuxtLink to="/" class="nav-link">Home</NuxtLink>
        </nav>
      </div>
    </header>
    <div class="mx-auto w-full max-w-6xl flex-1 px-4 py-8 sm:px-6">
      <slot />
    </div>
  </div>
</template>
