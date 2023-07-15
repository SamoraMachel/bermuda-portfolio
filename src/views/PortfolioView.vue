<script setup>
import HeroSection from '../components/HeroSection.vue'
import HomeSection from '../components/HomeSection.vue'
</script>

<template>
    <div>
        <HeroSection>
            <template #content>
                <HomeSection />
            </template>
        </HeroSection>
    </div>
</template>