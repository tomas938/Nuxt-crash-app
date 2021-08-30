<template>
  <div>
    id

    {{ product }}
  </div>
</template>

<script>
export default {
  computed: {
    product() {
      return this.$store.getters.getProductsById(this.$route.params.id)
    },
  },
}
</script>

<style scoped></style>
