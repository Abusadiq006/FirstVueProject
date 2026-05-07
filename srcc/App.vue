<script setup>
    import {ref} from 'vue'
   
    const year = ref('2014')

    import Header from '@/components/Header.vue'
</script>

<template>
    



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