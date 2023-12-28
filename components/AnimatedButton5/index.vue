<script setup lang="ts">
defineProps<{
  animation?: boolean
  offset?: boolean
}>()
</script>

<template>
  <button
    :data-glow-animation="animation"
    :data-glow-offset="offset"
    class="button glow-effect"
  >
    <slot />

    <svg class="glow">
      <rect pathLength="100" stroke-linecap="round" class="glow__blur"></rect>
      <rect pathLength="100" stroke-linecap="round" class="glow__line"></rect>
    </svg>
  </button>
</template>

<style lang="scss" scoped>
@import './AnimatedButton5.scss';
</style>
