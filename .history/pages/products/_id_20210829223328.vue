<template>
  <div>id</div>
</template>

<script>
export default {
  computed: {
    product() {
      return this.$store.getters.getProductById()
    },
  },
}
</script>

<style scoped></style>
