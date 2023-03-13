<template>
  <footer class="container py-5">
    <div class="row">
      <footer-logo/>
      <footer-menu/>
    </div>
  </footer>
</template>

<script>
import FooterLogo from './FooterLogo.vue'
import FooterMenu from './FooterMenu.vue'

  export default {
    name: 'FooterComponent',
    components: {
      FooterLogo,
      FooterMenu
    },
    data() {}
  }
</script>
