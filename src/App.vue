<script setup lang="ts">
import ShiningStar from './components/ShiningStar.vue'
</script>

<template>
  <main>
    <ShiningStar :animationDelayMs="100" />
    <ShiningStar :initialScale="0.7" />
    <ShiningStar :animationDelayMs="300" />
  </main>
</template>

<style scoped></style>
