<template>
  <div>

    <div class="bg-gray-100">
      <div class="container mx-auto space-x-4  h-10 flex items-center mb-10">
        <NuxtLink :to="{ name: 'a-empresa' }">A empresa</NuxtLink>
        <NuxtLink :to="{ name: 'servicos' }">Serviços</NuxtLink>
        <NuxtLink :to="{ name: 'produtos' }">Produtos</NuxtLink>
      </div>
    </div>
    <div class="container mx-auto">
      <Nuxt />
    </div>
  </div>
</template>

<style></style>
