<template>
  <div>
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue"
import MainComponent from "./components/MainComponent.vue"
import FooterComponent from "./components/FooterComponent.vue"


export default {
  name: 'DcSite',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
  }
}
</script>

<style lang="scss">
  @import "./assets/scss/style.scss"
</style>
