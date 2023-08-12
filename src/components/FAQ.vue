<template>
    <div class="flex">
        <div class="">
            <swiper :navigation="true" :modules="modules"  class="mySwiper">
                <swiper-slide>Slide 1</swiper-slide>
                <swiper-slide>Slide 2</swiper-slide><swiper-slide>Slide 3</swiper-slide>
            </swiper>
        </div>
    </div>
    
</template>
<script setup>
 import { Swiper, SwiperSlide } from 'swiper/vue';
 import { Navigation } from 'swiper/modules';
 
 
 const  modules =  [Navigation]
 
 
 
    
    
</script>
