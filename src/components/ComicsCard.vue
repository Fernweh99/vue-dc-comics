<template>
  <div class="col">
    <div class="container-image">
      <img class="card-image" :src="card.thumb" :alt="card.series">
    </div>
    <h3 class="h6">{{ card.series }}</h3>
  </div>
</template>

<script>
export default {
  name: "ComicsCard",
  props: {
    card : Object,
  }
}
</script>

<style lang="scss" scoped>
    .container-image {
    height:200px;
    .card-image {
      height: 100%;
      width: 100%;
      object-fit: cover;
      object-position: top;
    }
  }
</style>