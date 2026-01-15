<template>
    <div class="grid text-center">
        <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-5xl font-bold my-2">FAQ</h1>
        <span class="mx-auto text-center">Problems trying to resolve the conflict between the two major realms of
            Classical physics: Newtonian mechanics </span>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-4 mt-6 mx-auto">
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
            <FaqItem></FaqItem>
        </div>
    </div>
</template>
<script setup lang="ts">
import FaqItem from './FaqItem.vue';
</script>
<style scoped></style>