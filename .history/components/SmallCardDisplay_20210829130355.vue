<template>
  <div>
    <p>{{ cardSection.title }}</p>
    <div class="img">
      <SmallCard v-for="card in cardSection.cards"></SmallCard>
    </div>
  </div>
</template>

<script>
export default {
  props: ['cardSection'],
}
</script>

<style lang="scss" scoped></style>
