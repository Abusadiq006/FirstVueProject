<script setup>
    import { ref } from 'vue'
    const name = ref('Sadiq')
</script>

<template>
    <main>
        <h1>Hello, {{name}}!</h1>
        <p>I'm about to learn <a href="https://vuejs.org/" target="_blank">Maitashi</a>!</p>
    </main>
</template>

<style scoped>
    main h1 {
        display: block;
    }
    main a {
        color: #428883;
    }
</style>