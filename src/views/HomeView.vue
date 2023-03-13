<template>
  <div class="home">
    <header-component/>
    <main-component/>
    <footer-component/>
  </div>
</template>

<script>
import HeaderComponent from '@/components/header/HeaderComponent.vue'
import MainComponent from '@/components/main/MainComponent.vue'
import FooterComponent from '@/components/footer/FooterComponent.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  }
}
</script>
