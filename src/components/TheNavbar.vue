<template>
<div class="max-w-7xl mx-auto flex justify-between items-center h-20 p-5">
    <div class="text-4xl text-transparent bg-clip-text bg-gradient-to-r hover:bg-gradient-to-l from-indigo-500 via-purple-500 to-pink-500 cursor-pointer transition-all ease-in-out duration-1000 ">coinwave</div>
    <div class="block sm:hidden">
        menu
    </div>
    <nav class="hidden sm:inline-block">
        <ul class="flex gap-9 text-2xl">
            <RouterLink to="/" class="hover:text-purple-500 cursor-pointer transition-all ease-in-out duration-200">Home</RouterLink>
            <RouterLink to="/about" class="hover:text-purple-500 cursor-pointer transition-all ease-in-out duration-200">About</RouterLink>
            <li class="hover:text-purple-500 cursor-pointer transition-all ease-in-out duration-200">Prices</li>
            <li class="hover:text-purple-500 cursor-pointer transition-all ease-in-out duration-200">News</li>
        </ul>
    </nav>
</div>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>