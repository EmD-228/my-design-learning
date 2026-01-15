<script setup lang="ts">
import DemartmentsSection from './components/DemartmentsSection.vue';
import FAQ from './components/FAQ.vue';
import FeaturesSection from './components/FeaturesSection.vue';
import Footer from './components/Footer.vue';
import HeaderSection from './components/HeaderSection.vue';
import HeroSection from './components/HeroSection.vue';
import ImpressionSection from './components/ImpressionSection.vue';
import Newsletters from './components/Newsletters.vue';
import Testimonials from './components/Testimonials.vue';
</script>

<template>
  <div class="grid gap-10 container max-w-xs sm:max-w-[600px] md:max-w-[1000px] lg:max-w-[1200px]">
    <HeaderSection></HeaderSection>
    <HeroSection></HeroSection>
    <FeaturesSection></FeaturesSection>
    <DemartmentsSection></DemartmentsSection>
    <ImpressionSection></ImpressionSection>
    <Testimonials></Testimonials>
    <FAQ></FAQ>
    <Newsletters></Newsletters>
    <Footer></Footer>
  </div>
</template>

<style scoped></style>
