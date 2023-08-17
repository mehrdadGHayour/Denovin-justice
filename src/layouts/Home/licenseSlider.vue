<template>
  <div class="bg-secondary w-[1536px] h-[576px]">
    <img
      src="../../../public/images/Pattern2.png"
      alt=""
      class="absolute  select-none" />
    
  </div>
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
