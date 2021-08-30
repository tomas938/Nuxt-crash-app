<template>
  <div class="container">
    <h4 class="header">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Assumenda,
      dicta.
    </h4>
    <p class="snippet">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat a unde eum
      eaque molestiae ex.
    </p>
    <div class="card-container"></div>
  </div>
</template>

<script>
export default {
  props: [''],
}
</script>

<style scoped>
.container {
  margin-top: 2rem;
}
.header {
  font-weight: 700;
  font-size: 1.5rem;
}
.snippet {
  color: grey;
  margin-bottom: 1.5rem;
}
.cards-container {
  display: flex;
  justify-content: space-between;
}
</style>
