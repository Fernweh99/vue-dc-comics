<template>
  <div>
    <HeaderComponent/>
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue"

export default {
  name: 'DcSite',
  components: {
    HeaderComponent,
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

  ul li {
    display: inline-block;
  }

  a {
    display: inline-block;
    text-decoration: none;
  }

  body {
    font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;;
    background-color: #0E0E0E;
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
