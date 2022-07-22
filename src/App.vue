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
  // Generics
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  ul {
    list-style-type: none;
  }

  a {
    text-decoration: none;
  }

  body {
    font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;;
    background-color: #0E0E0E;
    color: #fff;
    padding: 15px 0;
  }
  img {
    height: auto;
    max-width: 100%;
  }
  // Utils
  .container {
    max-width: 1200px;
    margin: 0 auto;
  }
  .h-100 {
    height: 100%;
  }
</style>
