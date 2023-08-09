<template>
  <div class="bg-white rounded-lg shadow-md p-4">
    <h2 class="text-lg font-semibold text-gray-900">{{ title }}</h2>
    <p class="mt-2 text-gray-600">{{ description }}</p>
  </div>
</template>

<script setup>
const { title, description, imageSrc } = defineProps(['title', 'description', 'imageSrc'])
</script>
