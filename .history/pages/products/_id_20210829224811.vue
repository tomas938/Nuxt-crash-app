<template>
  <div>
    <div>id</div>
    <p>
      {{ $route.params.id }}
    </p>
  </div>
</template>

<script>
export default {
  computed: {
    product() {
      return console.log(this.$store.getters.getProductById($route.params.id))
    },
  },
}
</script>

<style scoped></style>
