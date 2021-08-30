<template>
  <div>
    <img :src="requie(`../assets/${card.image}`)" alt="" />
  </div>
</template>

<script>
export default {
  props: ['card'],
}
</script>

<style lang="scss" scoped></style>
