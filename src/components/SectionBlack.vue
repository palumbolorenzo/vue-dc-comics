<template>
  <div class="container-section">
  </div>
</template>

<script>
export default {
    name: 'SectionBlack',
}
</script>

<style lang="scss" scoped>
.container-section {
    background-image: url('@/img/jumbotron.jpg');
    background-position-x: center;
    height: 500px;
    padding: 0 5rem;
    display: flex;
    align-items: center;
}

h3 {
    color: white;
}
</style>