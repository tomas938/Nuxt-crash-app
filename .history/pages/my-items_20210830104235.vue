<template>
  <div>items</div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  layout: 'no-nav',
  computed: {
    ...mapState,
  },
}
</script>

<style scoped></style>
