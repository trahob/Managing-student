<script setup>
import topMenu from './components/topMenu.vue'
import swiperBar from './components/swiperBar.vue'
import SwiperCarousel from "./components/SwiperCarousel.vue";
</script>

<template>
    <topMenu/>
    <swiperBar/>
    <SwiperCarouselVue/>
    <img alt="Vue logo" src="./assets/logo.png" />
    <SwiperCarousel />
   
</template>

<style scoped>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
