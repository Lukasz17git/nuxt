<template>
   <div>
      event id: {{ route.params.id }}
   </div>
</template>

<script setup lang="ts">
const route = useRoute();
const id = route.params.id
console.log(id)

const nuxtApp = useNuxtApp()
console.log('nuxtApp', nuxtApp)
</script>