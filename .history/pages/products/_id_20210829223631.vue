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
      return this.$store.getters.getProductsId(this.$route.params.id)
    },
  },
}
</script>

<style scoped></style>
