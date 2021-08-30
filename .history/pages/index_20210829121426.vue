<template>
  <div class="container">
    <Hero></Hero>
    <LargeCardDisplay v-for=""></LargeCardDisplay>
  </div>
</template>

<script>
import { largeCardSections } from '../assets/data'
export default {
  data() {
    return {
      largeCardInfo: largeCardSections,
    }
  },
}
</script>
