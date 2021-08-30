<template>
  <div>
    <Nav></Nav>
    <div class="container">
      <LargeCardDisplay
        v-for="cardInfo in largeCardSections.slice(0, 1)"
        :key="cardInfo.id"
        :cardSection="cardInfo"
      ></LargeCardDisplay>
      <SmallCardDisplay
        v-for="cardInfo in smallCardSections"
        :key="cardInfo.id"
        :cardSection="cardInfo"
      ></SmallCardDisplay>
    </div>
  </div>
</template>

<script>
import { largeCardSections, smallCardSections } from '@/assets/data.js'
export default {
  data() {
    return {
      largeCardInfo: largeCardSections,
      smallCardSections,
    }
  },
}
</script>

<style scoped></style>
