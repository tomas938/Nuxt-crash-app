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
      return this.$store.getters.getProductById(Number(this.$route.params.id))
    },
  },
}
</script>

<style scoped></style>
