<template>
  <div class="activation">
    <header-component/>
    <form-activation/>
  </div>
</template>

<script>
import HeaderComponent from '@/components/header/HeaderComponent.vue'
import FormActivation from '@/components/forms/FormActivation.vue'

export default {
  name: 'ActivationView',
  components: {
    HeaderComponent, FormActivation
  }
}
</script>
