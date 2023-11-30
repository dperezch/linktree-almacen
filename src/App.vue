<template>
  <main class="bg-no-repeat bg-cover bg-center bg-[url('/shiny.svg')] w-screen h-screen">
    <section>
      <Logo/>
      <Welcome />
      <Enlaces />
    </section>
  </main>
</template>

<script setup lang="ts">
import Welcome from "./components/Welcome.vue"
import Enlaces from "./components/Enlances.vue"
import Logo from "./components/Logo.vue"

</script>

<style scoped>

</style>
