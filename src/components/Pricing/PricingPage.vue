<template>
          <div class="isolate bg-white px-6 py-12 lg:px-8">
            <div class="absolute inset-x-0 top-[-10rem] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[-20rem]" aria-hidden="true">
          
            <div class="relative left-1/2 -z-10 aspect-[1155/678] w-[36.125rem] max-w-none -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%-40rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
          </div>

           <div class="max-w-5xl mx-auto mt-8 px-6">
          <h2 class="text-2xl md:text-3xl font-semibold text-gray-900 text-center">Our Favourable Rates</h2>
        </div>
        <div class="max-w-5xl mx-auto mt-8 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <PricingSlab title="Static Sites" description="Affordable static websites to get your business online."
                price="Starting from $100" details="Perfect for small businesses and personal portfolios." />
            <PricingSlab title="Dynamic Sites" description="Take your website to the next level with dynamic features."
                price="Starting from $500" details="Ideal for businesses requiring interactive web applications." />
            <PricingSlab title="Large Sites & Maintenance"
                description="Comprehensive solutions for large-scale websites and ongoing maintenance."
                price="Starting from $1000" details="Tailored for enterprises and businesses with evolving needs." />
            <PricingSlab title="Programming Coaching" description="Get personalized programming coaching and guidance."
                price="Starting from $100" details="Perfect for individuals looking to enhance their coding skills." />
            <PricingSlab title="Cloud as a Service and Hosting"
                description="Host your applications and data securely on the cloud." price="$100"
                details="Perfect for startups and businesses requiring scalable cloud solutions." />
            <PricingSlab title="Pipeline Management" description="Efficiently manage your workflows and automate processes."
                price="$50" details="Ideal for streamlining business operations and increasing productivity." />
            <PricingSlab title="API Creation" description="Build custom APIs to integrate your applications and services."
                price="$50" details="Tailored for businesses seeking seamless data exchange and integrations." />
            <PricingSlab title="Mobile App Development"
                description="Get innovative and user-friendly mobile apps for your business." price="$500"
                details="Perfect for businesses aiming to expand their reach with mobile solutions." />
            <PricingSlab title="Computer Academic Tasks"
                description="Expert assistance with computer science academic tasks." price="$30+"
                details="Customized solutions for students and researchers." />
            <PricingSlab title="Design Systems" description="Create consistent and visually appealing design systems."
                price="$40+" details="Ideal for businesses and designers seeking a cohesive brand identity." />
            <PricingSlab title="Website Revamping" description="Give your existing website a fresh and modern look."
                price="$25+" details="Perfect for businesses looking to revamp their online presence." />
        </div>
    </div>
</template>

<script setup>

import PricingSlab from './PricingSlab.vue'

</script>
