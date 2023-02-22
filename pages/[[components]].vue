<script lang="ts" setup>
const route = useRoute()

if (route.path === '/components') {
  navigateTo('/')
}
</script>

<template>
  <NuxtLayout name="header">
    <NuxtPage />
  </NuxtLayout>
</template>
