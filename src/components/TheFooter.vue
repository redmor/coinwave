<template>
<footer class="h-[500px]">
<div class="max-w-7xl mx-auto flex justify-between h-20 p-5">
    <div>
        <div class="text-4xl text-transparent bg-clip-text bg-gradient-to-r hover:bg-gradient-to-l from-indigo-500 via-purple-500 to-pink-500 cursor-pointer transition-all ease-in-out duration-1000 ">coinwave</div>
        <p class="text-purple-300/50">Sam Rabili &copy;2023</p>
    </div>
    <div>
        <h2 class="text-2xl border-b-2 border-purple-500 mb-5">Navigation</h2>
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Prices</li>
            <li>News</li>
        </ul>
    </div>
    <div>
        <h2 class="text-2xl border-b-2 border-purple-500 mb-5">Social media</h2>
        <ul>
            <li>Facebook</li>
            <li>Instagram</li>
            <li>Twitter</li>
        </ul>
    </div>
</div>
</footer>
</template>

<script setup>

</script>

<style scoped>
    footer{
        background: url('/images/wave-haikei.svg');
        background-position: bottom;
        background-size: cover;
    }
</style>