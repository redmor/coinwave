<template>
  <TheNavbar />
  <div class="max-w-7xl mx-auto mt-10 grid grid-cols-12 ">
    <div class="col-span-5 self-center">
      <h1 class="text-6xl mb-5">Explore Crypto Assets, Prices and News</h1>
      <p class=" leading-8">Stay informed about the latest prices, trends, and breaking news of various cryptocurrencies on Cryptowatch, your go-to platform for the world of digital assets.</p>
      <button class="border-2 border-purple-600 px-8 py-3 rounded-3xl mt-5 text-purple-600 hover:text-purple-100 hover:bg-purple-600 transition-all ease-in-out duration-500">Read more</button>
    </div>
    <div class="col-span-7 justify-self-center bounce">
      <img class="w-[600px]" src="/images/cryptocurrency.png" alt="" />
    </div>
  </div>
</template>
<script setup>
import TheNavbar from "./TheNavbar.vue";
</script>

<style scoped>
.bounce {
  animation: bounce 2s ease-in-out infinite;
}
@keyframes bounce {
    0% { transform:translateY(0%); }
    50% { transform:translateY(-3%); }
    100% { transform:translateY(0); }
}
</style>