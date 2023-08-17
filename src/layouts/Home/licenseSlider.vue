<template>
    <div
      class="bg-secondary flex flex-col  sm:p-10 h-[576px]  items-end w-full gap-10 justify-end relative">
    <img src="/images/section1.png" alt="" class="absolute -top-1 left-1/2 -translate-x-1/2 w-[1920px] z-10">
      <div class=" self-start pt-3  w-full flex justify-between mt-10">
        <div>
          <div class="flex gap-4 ">
            <img src="/images/Pattern2.svg" alt="#" class="select-none absolute top-0 " />
          </div>
        </div>
        <div class="flex gap-5 mt-32 ml-16 justify-between items-center w-full">
          <div class="flex self-start just"><img src="/images/license.svg" alt=""></div>

          <div class="flex gap-3 ">
            <button class="bg-slate-700 rounded-full  z-[2]" @click="goBack">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="40"
              height="39"
              viewBox="0 0 40 39"
              fill="none">
              <path
                d="M12.3429 21.6121L23.2999 14.8613C23.5453 14.7109 23.8595 14.7253 24.0893 14.9029C25.1302 15.7046 26.0603 16.5174 26.6808 17.2006C26.6808 17.2006 27.2154 17.7479 27.4467 18.0951C27.8203 18.5687 28 19.1879 28 19.7896C28 20.4648 27.8031 21.1032 27.4107 21.6137C27.3216 21.7049 26.9825 22.1065 26.662 22.4345C24.7926 24.4762 19.9128 27.8492 17.3463 28.8716C16.9727 29.0364 15.9755 29.3805 15.4581 29.3997C14.9595 29.3997 14.4781 29.2909 14.0154 29.0524C13.4464 28.7244 13.001 28.2156 12.7509 27.6124C12.5899 27.1931 12.3414 25.9355 12.3414 25.8987C12.1804 25.001 12.06 23.7402 12.0006 22.2681C11.9897 22.0041 12.1225 21.7481 12.3429 21.6121Z"
                fill="white" />
              <path
                opacity="0.4"
                d="M13.076 17.9761C12.5931 18.2754 11.985 17.8929 12.0085 17.3185C12.0663 15.9712 12.1663 14.784 12.2883 13.9007C12.307 13.8815 12.5555 12.3151 12.8416 11.7854C13.3402 10.8014 14.3187 10.1998 15.3706 10.1998H15.4581C16.1365 10.2174 17.5792 10.819 17.5792 10.8558C18.306 11.1582 19.2548 11.6702 20.2754 12.2863C20.735 12.5647 20.7459 13.2479 20.2864 13.5311L13.076 17.9761Z"
                fill="white" />
            </svg>
          </button>
          <button class="bg-slate-700 rounded-full Slidebtn z-[2]" @click="goNext">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="39"
              height="39"
              viewBox="0 0 39 39"
              fill="none">
              <path
                d="M27.4571 17.7873L16.5001 24.5381C16.2547 24.6885 15.9405 24.6741 15.7108 24.4965C14.6698 23.6948 13.7398 22.882 13.1192 22.1988C13.1192 22.1988 12.5847 21.6515 12.3533 21.3043C11.9798 20.8307 11.8 20.2115 11.8 19.6098C11.8 18.9346 11.997 18.2962 12.3893 17.7857C12.4784 17.6945 12.8176 17.2929 13.138 16.9649C15.0074 14.9232 19.8872 11.5502 22.4538 10.5278C22.8273 10.363 23.8246 10.019 24.3419 9.99976C24.8405 9.99976 25.322 10.1086 25.7846 10.347C26.3536 10.675 26.799 11.1838 27.0491 11.787C27.2101 12.2063 27.4586 13.4639 27.4586 13.5007C27.6196 14.3984 27.74 15.6592 27.7994 17.1313C27.8103 17.3953 27.6775 17.6513 27.4571 17.7873Z"
                fill="white" />
              <path
                opacity="0.4"
                d="M26.724 21.4233C27.207 21.124 27.815 21.5065 27.7915 22.0809C27.7337 23.4282 27.6337 24.6154 27.5118 25.4987C27.493 25.5179 27.2445 27.0843 26.9584 27.614C26.4598 28.598 25.4814 29.1997 24.4294 29.1997L24.3419 29.1997C23.6635 29.1821 22.2208 28.5804 22.2208 28.5436C21.494 28.2412 20.5453 27.7292 19.5246 27.1131C19.065 26.8347 19.0541 26.1515 19.5136 25.8683L26.724 21.4233Z"
                fill="white" />
            </svg>
          </button>
          </div>
          

        </div>
      </div>
    
      <div class="w-full">
        <swiper-container
          ref="swiperRef"
          :slidesPerView="3"

          :breakpoints="{
            '300': {
              slidesPerView: 1,
              spaceBetween: 50,
            },
            '640': {
              slidesPerView: 1,
              spaceBetween: 40,
            },
            '768': {
              slidesPerView: 3,
              spaceBetween: 40,
            },
            '1024': {
              slidesPerView: 3,
              spaceBetween: 50,
            },
          }"
          class="mySwiper">
          <swiper-slide class="" v-for="number in num">
            <div class="">
              <img src="/images/Card.svg" alt="">
            </div>
          </swiper-slide>
        </swiper-container>
      </div>
    </div>
</template>

<script setup>
import { register } from "swiper/element/bundle";
import { ref } from "vue";

register();
const num = [1, 2, 3, 4, 5];

const swiperRef = ref(null);

const goNext = () => {
  swiperRef.value.swiper.slideNext();
};
const goBack = () => {
  swiperRef.value.swiper.slidePrev();
};
</script>
