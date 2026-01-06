<template>
    <div>
        <div class="relative">
            <img src="../assets/3.png" alt="Impression">
            <span
                class="flex gap-1 absolute top-2 left-2 px-2  bg-red-700 text-white text-xs font-bold rounded-sm">Sale</span>
            <div class="flex flex-row items-center gap-4 absolute bottom-2 left-1/2 icon-container -translate-x-1/2">
                <Icon class=" icon-item" icon="mdi:heart" style="color: black; font-size: 24px" />
                <Icon class=" icon-item" icon="mdi:cart" style="color: black" />
                <Icon class=" icon-item" icon="mdi:eye" style="color: black" />
            </div>
        </div>
        <div class="flex flex-col text-start gap-4 bg-white p-4">
            <div class="flex flex-row items-center justify-between gap-2">
                <h3 class="text-primary font-semibold">English Departement</h3>
                <div class="flex flex-row items-center gap-1 px-2 py-1 bg-secondary rounded-full">
                    <Icon class="" icon="mdi:star" style="color: yellow" />
                    <span>4.9</span>
                </div>
            </div>
            <span class="text-black font-bold text-md">Best dental surgeons</span>
            <p class="text-gray-500">We focus on ergonomics and meeting you where you work. It's only a keystroke away.
            </p>
            <div class="flex flex-row  items-center gap-1 w-fit">
                <Icon class="" icon="mdi:download" style="color: black; font-size: 24px" />
                <span class="text-gray-700 text-md font-bold">4.9</span>
            </div>
            <div class="flex flex-row  items-center gap-2 w-fit">
                <span class="text-gray-400 text-md font-bold">$100</span>
                <span class="text-blue-700 text-md font-bold">$100</span>
            </div>
            <div
                class="flex gap-2 items-center bg-white border border-primary text-primary px-4 py-2 rounded-full w-fit hover:bg-primary hover:text-white">
                Learn More
                <Icon class="" icon="mdi:arrow-right" style="color: var(--color-primary); font-size: 24px;" />
            </div>
        </div>
    </div>
</template>
<script setup lang="ts">
import { Icon } from '@iconify/vue';
</script>
<style scoped>
.icon-item {
    background-color: white;
    border-radius: 50%;
    padding: 5px;
    font-size: 24px;
    color: black;
}
</style>