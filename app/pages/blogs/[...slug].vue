<script setup>
const route = useRoute();
</script>



<template>
  <h2>Opps! Page Not found!</h2>
  <br />

  <p>
    You Tried to access: <strong> {{ route.params.slug.join("/") }}</strong>
  </p>
  <br />
  <NuxtLink to="/blogs">Go to Blogs Home</NuxtLink>
</template>
