<template>
  <div>
    <h3>Customer Reviews</h3>
    <div></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      reviewers: [],
    }
  },
  async fetch() {
    this.reviewers = await fetch().then((res) => res.json)
  },
}
</script>

<style scoped></style>
