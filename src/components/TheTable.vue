<script setup>

</script>

<template>
  <!-- <h2 class="text-center m-20 text-5xl text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500">Latest Prices</h2> -->
  <main class="max-w-7xl mx-auto  rounded-3xl px-5 m-20">
    <div class="flex flex-col">
  <div class="overflow-x-auto sm:-mx-6 lg:-mx-8">
    <div class="inline-block min-w-full py-2 sm:px-6 lg:px-8">
      <div class="overflow-hidden">
        <table class="min-w-full text-left text-sm font-light bg-sky-300/5">
          <thead class="border-b font-medium dark:border-neutral-500">
            <tr>
              <th scope="col" class="px-6 py-4">ID</th>
              <th scope="col" class="px-6 py-4">Name</th>
              <th scope="col" class="px-6 py-4">Price</th>
              <th scope="col" class="px-6 py-4">24h %</th>
              <th scope="col" class="px-6 py-4">Volume</th>
            </tr>
          </thead>
          <tbody>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">1</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">2</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-green-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">3</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">4</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">5</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-green-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">6</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">7</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-green-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">8</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">9</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
            <tr
              class="border-b transition duration-300 ease-in-out hover:bg-purple-900/30 border-neutral-500">
              <td class="whitespace-nowrap px-6 py-4 font-medium">10</td>
              <td class="whitespace-nowrap px-6 py-4">Bitcoin</td>
              <td class="whitespace-nowrap px-6 py-4">$26,000</td>
              <td class="whitespace-nowrap px-6 py-4 text-red-600">-2.00%</td>
              <td class="whitespace-nowrap px-6 py-4">$9,125,421.2</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</div>
  </main>
</template>
