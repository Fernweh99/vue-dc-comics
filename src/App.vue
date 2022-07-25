<template>
  <div>
    <HeaderComponent/>
    <main>
      <SectionComicsCard :comics-cards="comicsCards"/>
    </main>
    <FooterComponent/>
  </div>
</template>

<script>
import {comicsCards} from './assets/data/index.js'
import HeaderComponent from "./components/HeaderComponent.vue"
import SectionComicsCard from "./components/SectionComicsCard.vue"
import FooterComponent from "./components/FooterComponent.vue"


export default {
  name: 'DcSite',
  components: {
    HeaderComponent,
    SectionComicsCard,
    FooterComponent,
  },
  data(){
    return {
      comicsCards,
    }
  }
}
</script>

<style lang="scss">
  @import "./assets/scss/style.scss"
</style>
