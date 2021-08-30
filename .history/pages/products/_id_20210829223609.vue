<template>
  <div>
    id

    {{ $route.params.id }}
  </div>
</template>

<script>
export default {
  computed: {
    product() {
      return this.$store.getters.getProductById(this.$route.params.id)
    },
  },
}
</script>

<style scoped></style>
