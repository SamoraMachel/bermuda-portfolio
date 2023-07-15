<script setup>
import FeatureSection from '../components/FeatureSection.vue'
import HeroSection from '../components/HeroSection.vue'
</script>

<template>
    <HeroSection>
        <template #content> 
            <FeatureSection/>
        </template>
    </HeroSection>
</template>