<template>
    <div class="relative bg-gray-100 px-6 py-24 sm:py-32 lg:overflow-visible lg:px-0">
        <div class="absolute inset-0 -z-10 overflow-hidden">
            <svg class="absolute left-[max(50%,25rem)] top-0 h-[64rem] w-[128rem] -translate-x-1/2 stroke-gray-200 [mask-image:radial-gradient(64rem_64rem_at_top,white,transparent)]"
                aria-hidden="true">
                <!-- ... (existing SVG code remains unchanged) ... -->
            </svg>
        </div>
        <div
            class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 lg:mx-0 lg:max-w-none lg:grid-cols-2 lg:items-start lg:gap-y-10">
            <div
                class="lg:col-span-2 lg:col-start-1 lg:row-start-1 lg:mx-auto lg:grid lg:w-full lg:max-w-7xl lg:grid-cols-2 lg:gap-x-8 lg:px-8">
                <div class="lg:pr-4">
                    <div class="lg:max-w-lg">
                        <p class="text-base font-semibold leading-7 text-indigo-600">Elevate Your Business</p>
                        <h1 class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Bermuda Software
                            Solutions</h1>
                        <p class="mt-6 text-xl leading-8 text-gray-700">
                            Accelerate your success with our bespoke software solutions. We build robust systems from
                            scratch, delivering on-time with exceptional quality and design.
                        </p>
                    </div>  
                </div>
            </div>
            <div
                class="-ml-12 -mt-12 p-12 lg:sticky lg:top-4 lg:col-start-2 lg:row-span-2 lg:row-start-1 lg:overflow-hidden">
                <img class="w-[48rem] max-w-none rounded-xl bg-gray-900 shadow-xl ring-1 ring-gray-400/10 sm:w-[57rem]"
                    src="https://tailwindui.com/img/component-images/dark-project-app-screenshot.png"
                    alt="Software Solution Screenshot" />
            </div>
            <div
                class="lg:col-span-2 lg:col-start-1 lg:row-start-2 lg:mx-auto lg:grid lg:w-full lg:max-w-7xl lg:grid-cols-2 lg:gap-x-8 lg:px-8">
                <div class="lg:pr-4">
                    <div class="max-w-xl text-base leading-7 text-gray-700 lg:max-w-lg">
                        <p>
                            Our mission is to empower your business with cutting-edge technology. We provide top-tier
                            software development services, including:
                        </p>
                        <ul role="list" class="mt-8 space-y-8 text-gray-600">
                            <li class="flex gap-x-3">
                                <CloudArrowUpIcon class="mt-1 h-5 w-5 flex-none text-indigo-600" aria-hidden="true" />
                                <span>
                                    <strong class="font-semibold text-gray-900">Rapid Deployment:</strong> Accelerate your
                                    go-to-market strategy with our streamlined development process.
                                </span>
                            </li>
                            <li class="flex gap-x-3">
                                <LockClosedIcon class="mt-1 h-5 w-5 flex-none text-indigo-600" aria-hidden="true" />
                                <span>
                                    <strong class="font-semibold text-gray-900">Secure Solutions:</strong> Rest assured with
                                    our robust security measures and SSL certificates.
                                </span>
                            </li>
                            <li class="flex gap-x-3">
                                <ServerIcon class="mt-1 h-5 w-5 flex-none text-indigo-600" aria-hidden="true" />
                                <span>
                                    <strong class="font-semibold text-gray-900">Data Integrity:</strong> We ensure reliable
                                    database backups for your peace of mind.
                                </span>
                            </li>
                        </ul>
                        <p class="mt-8">
                            Our experienced team of developers is committed to delivering excellence. We prioritize your
                            success and believe that technology should
                            enhance your business, not hinder it. Let us handle the technicalities while you focus on your
                            core objectives.
                        </p>
                        <h2 class="mt-16 text-2xl font-bold tracking-tight text-gray-900">Scalable Solutions</h2>
                        <p class="mt-6">
                            With our scalable solutions, you can grow your business without limits. We ensure your systems
                            are flexible and adaptable to meet your
                            evolving needs. Experience the power of future-proof technology and stay ahead of the
                            competition.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { CloudArrowUpIcon, LockClosedIcon, ServerIcon } from '@heroicons/vue/20/solid';
</script>
