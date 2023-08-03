<template>
    <div class="bg-white rounded-lg shadow-md px-6 py-8">
        <h2 class="text-xl font-semibold text-gray-900">{{ title }}</h2>
        <p class="mt-2 text-gray-600">{{ description }}</p>
        <div class="mt-4">
            <h3 class="text-lg font-medium text-gray-900">{{ price }}</h3>
            <p class="mt-2 text-gray-600">{{ details }}</p>
        </div>

    </div>
</template>

<script setup>
const { title, description, price, details } = defineProps(['title', 'description', 'price', 'details'])
</script>
