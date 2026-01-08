<template>
    <div class="my-40">

        <h1 class="text-4xl font-bold my-6">FAQ</h1>
        <span class="mx-16 text-center max-w-md">Problems trying to resolve the conflict between the two major realms of
            Classical physics: Newtonian mechanics </span>
        <div class="w-3xl grid grid-cols-3 gap-4 mt-6 mx-auto">
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