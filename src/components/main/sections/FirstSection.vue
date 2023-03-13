<template>
  <div class="position-relative overflow-hidden p-3 p-md-5 m-md-3 text-center bg-light">
    <div class="col-md-5 p-lg-5 mx-auto my-5">
      <h1 class="display-4 fw-normal">{{ title }}</h1>
      <p class="lead fw-normal">{{ description }}</p>
      <router-link to="/catalog"><button class="btn btn-outline-secondary">{{ btnAction }}</button></router-link>
    </div>
    <div class="product-device shadow-sm d-none d-md-block"></div>
    <div class="product-device product-device-2 shadow-sm d-none d-md-block"></div>
  </div>  
</template>

<script>
  export default {
    name: 'FirstSection',
    components: {

    },
    data() {
      return {
        title: 'Modern Robot',
        description: 'Simplify your life with our robots. Buy a robot now on our website - covenient and profitable',
        btnAction: 'View catalog'
      }
    }
  }
</script>

<style>
  
</style>
