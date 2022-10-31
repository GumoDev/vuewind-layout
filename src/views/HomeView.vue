<script setup>
  import { ref } from 'vue';

 let message = ref('Happy Coding !!!')
</script>

<template>
  <section class="flex flex-col justify-center items-center  bg-gray-900 text-white h-[calc(100vh-64px)]">
    <h1 class="text-center p-2 text-xl">Home View</h1> 
    <h2 class="">
      Layout made with 
      <a href="https://vuejs.org/" class="bg-green-400 text-white px-3 rounded mx-2">
        Vue 3
      </a> + 
      <a href="https://vitejs.dev/" class="bg-violet-400 text-white px-3 rounded mx-2">
        Vite
      </a> + 
      <a href="https://tailwindcss.com/" class="bg-blue-300 text-white px-3 rounded mx-2">
        Tailwind
      </a> 
    </h2>

    <div class="logos flex my-5">
      <img class="h-20 w-20 mx-5" src="../assets/logo.svg" alt="logo-vue">
      <img class="h-20 w-20 mx-5" src="../assets/logo-vite.png" alt="logo-vite">
      <img class="h-20 w-20 mx-5" src="../assets/Tailwind_CSS_Logo.svg.png" alt="logo-tailwind">
    </div>

    <div class="start my-5 flex flex-col justify-center items-center ">
      <h3 class="text-3xl  my-5 bg-gradient-to-r from-green-400 via-purple-400 to-blue-300 text-white px-3 py-1 rounded animate-pulse">
        {{ message }}
      </h3>
      <img class=" h-96 rounded-lg  " src="../assets/dribbble-code.gif" alt="">
    </div>
  </section>
</template>

