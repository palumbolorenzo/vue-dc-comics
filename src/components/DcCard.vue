<template>
  <div class="card">
    <div class="contents">
        <img
          :src="dc.thumb"
          :alt="dc.series"
        >
        <h2>{{ card.series }}</h2>
    </div>
  </div>
</template>

<script>
export default {
name: 'DcCard',
props: {
    card: Object,
},
};
</script>

<style lang="scss" scoped>
  .card {
    text-align: center;
    padding: .1rem;
    .contents {
      padding: 1em;
      height: 100%;
      img {
        max-width: 90%;
      }
      h2 {
        font-size: 1.2rem;
      }
    }
  }
</style>