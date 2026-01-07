<template>
    <div class="my-40">
        <h2 class="text-primary ">Practice Advises</h2>
        <h1 class="text-4xl font-bold my-6">Each and every client is important.</h1>
        <span class="mx-16 text-center max-w-md">Problems trying to resolve the conflict between the two major realms of
            Classical physics: Newtonian mechanics </span>
        <div class="carousel rounded-box max-w-5xl space-x-4 p-4  mt-4">
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
            <div class="carousel-item">
                <TestimonialItem></TestimonialItem>
            </div>
        </div>

    </div>
</template>
<script setup lang="ts">
import TestimonialItem from './TestimonialItem.vue';
</script>