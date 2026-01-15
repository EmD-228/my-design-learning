<template>
    <div class="grid">
        <h2 class="text-primary ">Practice Advises</h2>
        <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-5xl font-bold my-2">See Our Impressions</h1>
        <span class="mx-auto">Problems trying to resolve the conflict between the two major realms of Classical physics:
            Newtonian mechanics </span>

        <div class="grid sm:grid-cols-2 gap-4 mt-6 justify-center items-center lg:place-content-center">
            <ImpressionItem></ImpressionItem>
            <ImpressionItem></ImpressionItem>
        </div>
    </div>
  
</template>
<script setup lang="ts">
import ImpressionItem from './ImpressionItem.vue';
</script>