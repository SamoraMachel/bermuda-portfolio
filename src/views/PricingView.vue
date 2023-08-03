<script setup>
import PricingPage from '../components/Pricing/PricingPage.vue'
import HeroSection from '../components/HeroSection.vue'
import IntroSection from '../components/Pricing/introSection.vue'
</script>

<template>
    <HeroSection>
        <template #content>
            <HeroSection />
            <IntroSection />
            <PricingPage />
        </template>
    </HeroSection>
</template>