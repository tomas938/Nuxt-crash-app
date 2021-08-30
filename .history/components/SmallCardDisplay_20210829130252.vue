<template>
  <div>
    <p>{{ cardSection.title }}</p>
    <div class="img">
      <SmallCard></SmallCard>
    </div>
  </div>
</template>

<script>
export default {
  props: ['cardSection'],
}
</script>

<style lang="scss" scoped></style>
