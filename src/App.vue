<template>
  <pageHeader />
  <main class="h-[300vh]">
    <Section1 />
    <licenseSlider />
    <contactUs />
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
import contactUs from "./layouts/Home/contactus.vue"
</script>

<style scoped></style>
