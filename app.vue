<template>

  <!-- Navigation -->
  <nav class="bg-slate-900 py-6 flex justify-center">
    <ul class="flex gap-20"> 
      <li class="text-white"><NuxtLink :to="{ name: 'index' }">Home</NuxtLink></li>
      <li class="text-white"><NuxtLink :to="{ name: 'about' }">About</NuxtLink></li>
      <li class="text-white"><NuxtLink :to="{ name: 'store' }">Store</NuxtLink></li>
      <li class="text-white"><NuxtLink :to="{ name: 'guide' }">Guide</NuxtLink></li>
    </ul>
  </nav>

  <!-- Content Section -->
  <section class="min-h-screen bg-slate-800 text-white">
    <NuxtPage />
  </section>
</template>