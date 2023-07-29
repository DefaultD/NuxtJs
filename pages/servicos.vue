<template>
  <div>
    <div class="container mx-auto">
      <h1 class="text-lg font-bold"> Serviços</h1>
      <NuxtLink to="/servicos/desenvolvimento-de-sites">
        Desenvolvimento de sites
      </NuxtLink>
      <NuxtLink to="/servicos/marketing-digital">
        Marketing Digital
      </NuxtLink>
      <br />
      <NuxtChild />
    </div>
  </div>
</template>

<script lang="ts">
name: 'servico'

export default {

}
</script>
