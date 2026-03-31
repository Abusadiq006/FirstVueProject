<script setup lang="ts">
  import {ref} from 'vue'
  const name = ref('Sadiq')
  const emoji = ref('✌')
</script>

<template>
  <header>
    <span>{{ emoji }}</span>
  </header>

  <main>
    <h1>Hello, {{ name }}!</h1>
    <p>I'am a Software Developer <a href="https://vuejs.org" target="_blank">Vue</a></p>
  </main>

  <footer>
    <p>&copy; 2026</p>
  </footer>
</template>

<style scoped>
  header span{
    font-size: 3rem;
  }
</style>
