<template>
  <footer>
    <FooterTopComponent/>
    <FooterBottomComponent/>
  </footer>
</template>

<script>
import FooterTopComponent from "./FooterComponents/FooterTopComponent.vue"
import FooterBottomComponent from "./FooterComponents/FooterBottomComponent.vue"

export default {
  name: 'FooterComponent',
  components: {
    FooterTopComponent,
    FooterBottomComponent,
  }
}
</script>

<style>

</style>