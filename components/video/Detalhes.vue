<template>
  <h1>Componentes - Nuxt 3</h1>
  <p>Nuxt 3 && Vue 3</p>
  <p>{{ diferencaEmDias }} dias atrás</p>
</template>

<script setup lang="ts">
const {diasPassados, diferencaEmDias} = useFormatacao()

const dataVideo = new Date(2023, 9, 2)

diasPassados(dataVideo)

</script>

<style>

</style>