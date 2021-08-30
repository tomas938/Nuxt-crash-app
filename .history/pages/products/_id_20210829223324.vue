<template>
  <div>id</div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  computed: {
    product() {
      return this.$store.getters.getProductById()
    },
  },
}
</script>

<style scoped></style>
