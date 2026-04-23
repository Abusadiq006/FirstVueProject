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
    <h1>Hello</h1>
</main>
</template>

<style scoped>
</style>