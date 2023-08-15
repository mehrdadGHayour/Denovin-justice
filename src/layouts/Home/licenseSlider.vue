<template>
  <h1>modix</h1>
  <img
    src="/images/.svg"
    alt=""
    class="absolute -z-30 select-none" />
</template>

<script>
import { register } from "swiper/element/bundle";
import { Pagination } from "swiper/modules";
import { ref } from "vue";

register();
const modules = [Pagination];
const num = [1, 2, 3, 4, 5];

const swiperRef = ref(null);

const goNext = () => {
  swiperRef.value.swiper.slideNext();
};
</script>

<style scoped></style>
