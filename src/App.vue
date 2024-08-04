<script setup lang="ts">
import Menu from './components/Menu.vue'
</script>

<template>

  <div class="w-full h-[100vh] bg-white" >
      <header class="flex justify-center h-1/4 w-full" >
          <nav  class="flex justify-evenly items-center w-3/4 border border-black mt-5" >
              <Menu/>
          </nav>
      </header>
  </div>

</template>

<style scoped>

</style>
