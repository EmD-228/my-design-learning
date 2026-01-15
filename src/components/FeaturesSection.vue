<template>
    <div class="">
        <p class="text-primary ">Practice Advises</p>
        <p class="text-xl sm:text-3xl md:text-4xl lg:text-5xl font-bold my-2">See Our Impressions</p>
        <span class="mx-auto">Problems trying to resolve the conflict between the two major realms of Classical physics:
            Newtonian mechanics </span>
        <div class="grid gap-4 mt-6 sm:grid-cols-2 justify-center">
            <FeatureItem ></FeatureItem>
            <FeatureItem></FeatureItem>
        </div>
    </div>
</template>

<script setup lang="ts">
import FeatureItem from './FeatureItem.vue';
</script>