<template>
  <div class="flex justify-center">
    <header class="fixed rounded-3xl w-[90%] h-16 flex items-center justify-center px-4 bg-red-800 text-white hover:shadow-xl hover:shadow-red-400 hover:translate-y-1 duration-500">
      <nav class="flex gap-8 text-lg justify-beetwen w-full">
        <span class="w-[60%] font-bold">N-INNOVATIONS BIOSUPPLY</span>
        <ul class="w-[40%] flex justify-center gap-8">
          <li><NuxtLink to="/">Inicio</NuxtLink></li>
          <li><NuxtLink to="/about">Sobre Nosotros</NuxtLink></li>
          <li><NuxtLink to="/contact">Contactos</NuxtLink></li>
        </ul>
      </nav>
  </header>
  </div>
    
  <main class="flex justify-center items-center flex-col w-full">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </main>
</template>
<style>
  li:hover{
    transform: scale(1.1);
  }
</style>