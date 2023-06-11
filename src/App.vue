<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheHero from './components/TheHero.vue';
</script>

<template>
  <header class=" bg-gradient-to-b from-indigo-900">
    <TheHero/>
  </header>
  <RouterView/>
</template>