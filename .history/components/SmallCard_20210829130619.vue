<template>
  <div>
    <img :src="require(`../assets/images/${card.image}`)" alt="" />
  </div>
</template>

<script>
export default {
  props: ['card'],
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
