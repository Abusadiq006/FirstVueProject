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
    <p></p>
</main>
</template>

<style scoped>
</style>