<template>
    <div class="grid">
        <h2 class="text-primary ">Practice Advises</h2>
        <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-5xl font-bold my-2">Each and every client is important.</h1>
        <span class="text-center mx-auto max-w-md">Problems trying to resolve the conflict between the two major realms of
            Classical physics: Newtonian mechanics </span>
        <div class="carousel rounded-box max-w-full space-x-4 p-4  mt-4">
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