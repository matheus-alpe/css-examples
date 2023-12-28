<template>
  <div class="container">
    <AnimatedButton5>Default</AnimatedButton5>
    <AnimatedButton5 animation>Animation</AnimatedButton5>
    <AnimatedButton5 offset>Offset</AnimatedButton5>
    <AnimatedButton5 animation offset>Animation + Offset</AnimatedButton5>
  </div>
</template>

<style scoped lang="scss">
.container {
  display: grid;
  gap: 20px;
  justify-items: center;
}
</style>
