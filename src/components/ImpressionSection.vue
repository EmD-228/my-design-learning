<template>
    <div class="my-40">
        <h2 class="text-primary ">Practice Advises</h2>
        <h1 class="text-4xl font-bold my-6">See Our Impressions</h1>
        <span class="mx-auto">Problems trying to resolve the conflict between the two major realms of Classical physics:
            Newtonian mechanics </span>

        <div class="grid grid-cols-4 gap-4 mt-6 justify-center items-center">
            <ImpressionItem ></ImpressionItem>
            <ImpressionItem></ImpressionItem>
        </div>
    </div>
</template>
<script setup lang="ts">
import ImpressionItem from './ImpressionItem.vue';
</script>