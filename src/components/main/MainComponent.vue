<template>
  <main>
    <first-section/>
    <advertising-section/>
  </main>
</template>

<script>
import FirstSection from './sections/FirstSection.vue'
import AdvertisingSection from './sections/AdvertisingSection.vue'

  export default {
    name: 'MainComponent',
    components: {
      FirstSection,
      AdvertisingSection 
    }
  }
</script>

<style>
  
</style>
