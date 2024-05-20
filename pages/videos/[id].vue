<template>
    <div>
      <h3>Você esta no videos de numero {{ $route.params.id }}</h3>
    </div>
      <VideoDetalhes />
      <VideoControlePlay />
  </template>
  
  <script>
    definePageMeta({
        layout: "exibicao",
        middleware: ["video", "auth"]
    })

    // const route = useRoute();

    // const idParams = computed(() => route.params.id)
  </script>
  
  <style lang="scss" scoped>
  
  </style>