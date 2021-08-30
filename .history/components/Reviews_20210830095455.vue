<template>
  <div>
    <h3>Customer Reviews</h3>
    <div>
      {{ reviewers }}
    </div>
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
    this.reviewers = await fetch('https://randomuser.me/api/?results=5').then(
      (res => res.json())
  }
}
</script>

<style scoped></style>
