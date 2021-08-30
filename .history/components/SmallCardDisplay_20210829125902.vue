<template>
  <div>
    <p>{{ cardInfo.title }}</p>
    <div class="img"></div>
  </div>
</template>

<script>
export default {
  props: ['cardInfo'],
}
</script>

<style lang="scss" scoped></style>
