<template>
  <div>
    <b-button id="show-btn" @click="showModal">Open Modal</b-button>

    <b-modal ref="my-modal" hide-footer title="Using Component Methods">
      .calendar
    </b-modal>
  </div>
</template>

<script>
export default {
  methods: {
    showModal() {
      this.$refs['my-modal'].show()
    },
    hideModal() {
      this.$refs['my-modal'].hide()
    },
    toggleModal() {
      // We pass the ID of the button that we want to return focus to
      // when the modal has hidden
      this.$refs['my-modal'].toggle('#toggle-btn')
    },
  },
}
</script>

<style lang="sass" scoped></style>
