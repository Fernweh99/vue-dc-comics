<template>
  <div class="container">
    <div class="row py-5 row-cols-6">
      <ComicsCard v-for="card in comicsCards" :key="card.series" :card="card"/>
    </div>
  </div>
</template>

<script>
import ComicsCard from "./ComicsCard.vue"

export default {
  name: 'SectionComicsCard',
  components: {
    ComicsCard,
  },
  props: {
    comicsCards : Array,
  }
}

</script>

<style lang="scss" scoped>

</style>