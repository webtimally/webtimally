<template>
  <the-header />
  <main>
    <page-intro />
    <about-us />
    <our-services />
    <how-we-work />
    <our-experts />
  </main>
  <the-footer />
</template>

<script setup>
import TheHeader from "@/components/page-components/the-header/TheHeader.vue";
import TheFooter from "@/components/page-components/the-footer/TheFooter.vue";

import PageIntro from "@/components/page-components/page-intro/PageIntro.vue";
import AboutUs from "@/components/page-components/about-us/AboutUs.vue";
import OurServices from "@/components/page-components/our-services/OurServices.vue";
import HowWeWork from "@/components/page-components/how-we-work/HowWeWork.vue";
import OurExperts from "@/components/page-components/our-experts/OurExperts.vue";
</script>