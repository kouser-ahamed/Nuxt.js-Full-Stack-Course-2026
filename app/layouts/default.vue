<template>
    <div class="flex min-h-screen flex-col">
        <header class="sticky top-0 z-20 border-b border-slate-800 bg-slate-900 shadow-sm">
            <div class="mx-auto flex w-full max-w-6xl flex-wrap items-center justify-between gap-x-6 gap-y-2 px-4 py-4 sm:px-6">
                <h2 class="text-lg font-semibold tracking-wide text-white">
                    Site Header
                </h2>
                <nav class="flex items-center gap-4">
                    <NuxtLink to="/" class="nav-link">Home</NuxtLink>
                    <NuxtLink to ="/admin" class="nav-link">Admin</NuxtLink>
                </nav>
            </div>
        </header>
        <main class="mx-auto w-full max-w-6xl flex-1 px-4 py-10 sm:px-6">

            <slot />

        </main>

        <footer class="border-t border-slate-800 bg-slate-900">
            <div class="mx-auto w-full max-w-6xl px-4 py-6 text-center text-sm text-slate-400 sm:px-6">
                Footer
            </div>
        </footer>
    </div>
</template>
