<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <header-component/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from '@/components/header/HeaderComponent.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderComponent
  }
}
</script>
