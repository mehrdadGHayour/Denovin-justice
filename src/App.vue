<template>
  <pageHeader />
  <main class="max-w-[100rem] mx-auto">
    <Section1 />
    <licenseSlider />
    <Aboutus />
    <Latest />
    <Section7 />
    <Contact />
    <FAQ />
  </main>
  <pageFooter />
</template>

<script setup>
import pageFooter from "./layouts/pageFooter.vue";
import pageHeader from "./layouts/pageHeader.vue";
import FAQ from "./components/FAQ.vue";
import Section1 from "./layouts/Home/Section1.vue";
import licenseSlider from "./layouts/Home/licenseSlider.vue";
import contactUs from "./layouts/Home/contactUs.vue";
import Aboutus from "./layouts/Home/Aboutus.vue";
import Section7 from "./layouts/Home/Section7.vue";
import Latest from "./layouts/Home/LatestArticle.vue";
import Contact from "./layouts/Home/contactUs.vue"
</script>

<style scoped></style>
