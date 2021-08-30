<template>
  <div>
    <img :src="require(`../assets/${card.image}`)" alt="" />
  </div>
</template>

<script>
export default {
  props: ['card'],
}
</script>

<style lang="scss" scoped></style>
