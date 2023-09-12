<script setup>
import Header from '../Componets/Header.vue';
import Footer from '../Componets/Footer.vue';
</script>
<template>
    <div class="container">
        <Header/>
        <slot/>
        <Footer/>
    </div>
</template>
