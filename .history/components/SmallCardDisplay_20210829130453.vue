<template>
  <div>
    <p>{{ cardSection.title }}</p>
    <div class="img">
      <SmallCard
        v-for="card in cardSection.cards"
        :key="card.id"
        :card="card"
      ></SmallCard>
    </div>
  </div>
</template>

<script>
export default {
  props: ['cardSection'],
}
</script>

<style lang="scss" scoped></style>
