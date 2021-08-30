<template>
  <div>
    <b-button id="show-btn" @click="showModal">Rent</b-button>

    <b-modal ref="my-modal" hide-footer title="Using Component Methods">
      <div class="calendar-container">
        <div class="text-container">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas nam
            deserunt doloremque illo? Incidunt esse perspiciatis alias voluptas
            ullam reprehenderit quos atque vel qui illum. Autem suscipit
            consequuntur iusto libero quod velit deleniti fugit, esse illo
            laborum vero aut iure.
          </p>
        </div>
      </div>
      <b-button id="show-btn" variant="outline-danger">Order</b-button>
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
