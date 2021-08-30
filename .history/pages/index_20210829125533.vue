<template>
  <div class="container">
    <Hero></Hero>
    <LargeCardDisplay
      v-for="cardInfo in largeCardInfo"
      :key="cardInfo.id"
      :cardSection="cardInfo"
    ></LargeCardDisplay>
    <SmallCardDisplay> </SmallCardDisplay>
  </div>
</template>

<script>
import { largeCardSections } from '../assets/data'
import { smallCardSections } from '../assets/data'
export default {
  data() {
    return {
      largeCardInfo: largeCardSections,
    }
  },
}
</script>
