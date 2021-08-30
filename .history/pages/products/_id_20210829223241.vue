<template>
  <div>id</div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  computed: {
    product() {
      return this.$store
    },
  },
}
</script>

<style scoped></style>
