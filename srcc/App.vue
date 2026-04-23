<script setup>
    import {ref} from 'vue'
    const name = ref('Sadiq')
    const emoji = ref('😎')
</script>

<template>
    <header>
        <span>{{emoji}}</span>
    </header>

<main>
    <h1>Hello, {{name}}!</h1>
    <p>I'm about to learn <a href="https://vuejs.org/" target="_blank">Maitashi</a>!</p>
</main>

<footer></footer>
</template>

<style scoped>
</style>