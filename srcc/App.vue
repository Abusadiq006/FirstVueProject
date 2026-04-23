<script setup>
    import {ref} from 'vue'
    const name = ref('Sadiq')
    const emoji = ref('😎')
    const year = ref('2014')
</script>

<template>
    <header>
        <span>{{emoji}}</span>
    </header>

<main>
    <h1>Hello, {{name}}!</h1>
    <p>I'm about to learn <a href="https://vuejs.org/" target="_blank">Maitashi</a>!</p>
</main>

<footer>
    <p>&copy</p>
</footer>
</template>

<style scoped>
    header span {
        font-size: 3rem;
    }
    main h1 {
        display: block;
    }
    main a {
        color: #428883;
    }
    footer {
        position: fixed;
        bottom: 0;
        padding-bottom: 20px;
    }
</style>