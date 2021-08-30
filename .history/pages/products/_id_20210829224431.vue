<template>
  <div>id</div>
  <p>
    {{ product }}
  </p>
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
