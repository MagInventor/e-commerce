<template>
  <div class="home">
    <header-component/>
    <main-component/>
  </div>
</template>

<script>
import HeaderComponent from '@/components/header/HeaderComponent.vue'
import MainComponent from '@/components/main/MainComponent.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderComponent,
    MainComponent
  }
}
</script>
