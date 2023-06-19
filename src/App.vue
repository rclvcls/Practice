<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>
   <RouterView />
</template>
