<template>
  <div class="about">
    <header-component/>
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import HeaderComponent from '@/components/header/HeaderComponent.vue'

export default {
  name: 'AboutView',
  components: {
    HeaderComponent
  }
}
</script>
