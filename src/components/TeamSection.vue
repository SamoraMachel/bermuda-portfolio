<template>
    <div class="bg-white py-24 sm:py-32">
      <div class="mx-auto grid max-w-7xl gap-x-8 gap-y-20 px-6 lg:px-8 xl:grid-cols-3">
        <div class="max-w-2xl">
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Meet the Team</h2>
          <p class="mt-6 text-lg leading-8 text-gray-600">
            At Bermuda, we pride ourselves on having a team of exceptional individuals who are passionate about software transformation 
            and dedicated to delivering outstanding results. Meet the talented professionals who will work tirelessly to turn your software into market-ready products:
          </p>
        </div>
        <ul role="list" class="grid gap-x-8 gap-y-12 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2">
          <li v-for="person in people" :key="person.name">
            <div class="flex items-center gap-x-6">
              <img class="h-16 w-16 rounded-full" :src="person.imageUrl" alt="" />
              <div>
                <h3 class="text-base font-semibold leading-7 tracking-tight text-gray-900">{{ person.name }}</h3>
                <p class="text-sm font-semibold leading-6 text-indigo-600">{{ person.role }}</p>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </template>
  
  <script setup>
  const people = [
    {
      name: 'Samora Machel',
      role: 'Mobile and Backend Engineer',
      imageUrl:
        'https://images.unsplash.com/photo-1552234994-66ba234fd567?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8cG90cmFpdHxlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=500&q=60',
    },
    {
      name: 'Daniel Ochieng',
      role: 'UI/UX Designer and FrontEnd Engineer',
      imageUrl:
        'https://images.unsplash.com/photo-1463453091185-61582044d556?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fHBvdHJhaXQlMjBibGFja3xlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=500&q=60',
    },
    {
      name: 'Joel Koyoo',
      role: 'Backend and DevOps Engineer',
      imageUrl:
        'https://images.unsplash.com/photo-1509305717900-84f40e786d82?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8cG90cmFpdCUyMGJsYWNrfGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60',
    },
    {
      name: 'Moses',
      role: 'FrontEnd Engineer',
      imageUrl:
        'https://images.unsplash.com/photo-1484517186945-df8151a1a871?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTB8fHBvdHJhaXQlMjBibGFja3xlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=500&q=60',
    },
  ]
  </script>