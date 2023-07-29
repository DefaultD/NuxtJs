<template>
  <div>

    <div class="container mx-auto">
      <h1 class="text-lg font-bold"> Produtos</h1>
      <NuxtLink :to="{ name: 'produtos-produtos-a' }">Produtos a</NuxtLink>
      <NuxtLink :to="{ name: 'produtos-produtos-b' }">Produtos b</NuxtLink>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's
        standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a
        type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting,
        remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing
        Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.</p>
    </div>
  </div>
</template>

<script lang="ts">
name: 'produtos'

export default {

}
</script>
