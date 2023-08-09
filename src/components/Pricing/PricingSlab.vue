<template>
    <div class="bg-white p-6 text-center">
        <h3 class="text-xl font-semibold text-gray-900 mb-2">{{ title }}</h3>
        <p class="text-gray-600">{{ description }}</p>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

const { title, description } = defineProps({
    title: String,
    description: String,
});
</script>

<style scoped>
/* Remove the box shadow */
</style>
