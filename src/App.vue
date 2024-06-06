<script setup>
import topMenu from './components/topMenu.vue'
import menuFood from './components/menuFood.vue'
import SwiperCaroucel from './components/SwiperCaroucel.vue'
// import SwiperCarousel from "./components/SwiperCarousel.vue";
</script>

<template>
    <div class="topMenu" >
        <topMenu/>
    </div>
    <div>
        <SwiperCaroucel/>
    </div>
    
    <div>
        <menuFood/>
    </div>
</template>

<style scoped>
    
</style>
