<script lang="ts" setup>
const links = ref([
  {
    url: '1-card-product',
    name: '1 - Card Product',
  },
  {
    url: '2-card-product',
    name: '2 - Card Product',
  },
  {
    url: '3-card-product',
    name: '3 - Card Product',
  },
  {
    url: '4-animated-border',
    name: '4 - Animated Border',
  },
  {
    url: '5-animated-button',
    name: '5 - Animated Button',
  },
])
</script>

<template>
  <nav>
    <ul>
      <li
        v-for="(link, index) in links"
        :key="index"
      >
        <NuxtLink :to="link.url">{{ link.name }}</NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss">
ul {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}
</style>
