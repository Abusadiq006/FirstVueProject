<script setup>
    import {ref} from 'vue'
    const name = ref('Sadiq')
    const year = ref('2014')

    import Header from '@/components/Header.vue'
</script>

<template>
    

<main>
    <h1>Hello, {{name}}!</h1>
    <p>I'm about to learn <a href="https://vuejs.org/" target="_blank">Maitashi</a>!</p>
</main>

<footer>
    <p>&copy; {{year}}</p>
</footer>
</template>

<style scoped>
   
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
    footer p {
        color: blue;
    }
</style>