<template>
  <div class="container">
    <Hero></Hero>
    <LargeCardDisplay
      v-for="cardInfo in largeCardInfo"
      :key="cardInfo.id"
      :cardSection="cardInfo"
    ></LargeCardDisplay>
    <SmallCardDisplay
      v-for="card in smallCardInfo"
      :key="card.info"
      :card="card"
    >
    </SmallCardDisplay>
  </div>
</template>

<script>
import { largeCardSections } from '../assets/data'
import { smallCardSections } from '../assets/data'
export default {
  data() {
    return {
      largeCardInfo: largeCardSections,
      smallCardInfo: smallCardSections,
    }
  },
}
</script>
