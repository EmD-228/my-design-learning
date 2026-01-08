<template>
    <div class="w-[300px] flex flex-nowrap flex-col items-center gap-4 bg-white p-6">
        <img class="w-32 h-32 rounded-full" src="../assets/3.png" alt="Testimonial 1">
        <p class="text-black">The gradual accumulation and small-scale..</p>
        <div class="flex flex-row items-center gap-2">
            <Icon class="" icon="mdi:star" style="color: orange" />
            <Icon class="" icon="mdi:star" style="color: orange" />
            <Icon class="" icon="mdi:star" style="color: orange" />
            <Icon class="" icon="mdi:star" style="color: orange" />
            <Icon class="" icon="mdi:star" style="color: gray" />
        </div>
        <span class="text-black font-bold leading-none">Regina Miles</span>
        <span class="text-gray-500 leading-none">UX Designer</span>
    </div>
</template>
<script setup lang="ts">
import { Icon } from '@iconify/vue';
</script>
<style scoped>

</style>