<script setup>
import HeroSection from '../components/HeroSection.vue'
import HomeSection from '../components/HomeSection.vue'
import FeatureSection from '../components/FeatureSection.vue';  
import TeamSection from '../components/TeamSection.vue';    
import ContactSection from '../components/ContactSection.vue';
</script>

<template>
    <div>
        <HeroSection>
            <template #content>
                <HomeSection />
                <FeatureSection />
                <TeamSection />
                <ContactSection />
            </template>
        </HeroSection>
    </div>
</template>