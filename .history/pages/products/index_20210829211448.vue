<template>
  <div class="container">
    <LargeCardDisplay
      v-for="cardInfo in largeCardSections.slice(0, 1) :key="cardInfo.id"
    ></LargeCardDisplay>
  </div>
</template>

<script>
import { largeCardSections, smallCardSections } from '@/assets/data.js'
export default {}
</script>

<style scoped></style>
