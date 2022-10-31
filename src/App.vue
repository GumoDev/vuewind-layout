<script setup>
  import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class=" bg-gradient-to-r from-green-400 via-purple-400 to-blue-300 flex items-center text-white py-3">
    <img alt="Vue logo" class="logo h-10" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <nav>
        <RouterLink  class="mx-2" to="/">Home</RouterLink>
        <RouterLink class="mx-2" to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style  >
  body {
    font-family: 'Chakra Petch', sans-serif;
  }
</style>
