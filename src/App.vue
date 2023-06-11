<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheHero from './components/TheHero.vue';
import TheFooter from './components/TheFooter.vue';
</script>

<template>
  <header class=" bg-gradient-to-b from-indigo-900">
    <TheHero/>
  </header>
  <RouterView/>
<TheFooter/>
</template>