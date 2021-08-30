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

<style scoped></style>
