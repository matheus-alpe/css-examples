<template>
  <header class="header">
    <NuxtLink
      class="cta-back"
      to="/"
      >Back</NuxtLink
    >
  </header>
  <slot />
</template>

<style lang="scss">
.header {
  margin-bottom: 4em;
}
</style>
