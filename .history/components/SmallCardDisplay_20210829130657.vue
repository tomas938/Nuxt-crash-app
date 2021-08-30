<template>
  <div class="container">
    <h3>{{ cardSection.title }}</h3>
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

<style scoped>
.container {
  padding: 2rem 0;
}
.header {
  font-weight: 700;
  font-size: 1.5rem;
  margin-bottom: 2rem;
}
.card-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
</style>
