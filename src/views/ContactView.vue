<script setup>
import ContactSection from '../components/ContactSection.vue'
import TeamSection from '../components/TeamSection.vue'
import HeroSection from '../components/HeroSection.vue'
</script>

<template>
    <HeroSection>
        <template #content>
            <ContactSection />  
            <TeamSection />
        </template>
    </HeroSection>
</template>