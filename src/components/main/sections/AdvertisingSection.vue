<template>
  <section class="second-section">
    <div class="container">
      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
        <advertising-item/>
        <advertising-item/>
        <advertising-item/>
      </div>
    </div>
  </section>
</template>

<script>
import AdvertisingItem from './AdvertisingItem.vue'

  export default {
    name: 'AdvertisingSection',
    components: {
      AdvertisingItem
    },
    data() {
      return {}
    }
  }
</script>

<style>
  .second-section {
    padding: 20px 0;
  }

/*  .bd-placeholder-img {
    font-size: 1.125rem;
    text-anchor: middle;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none;
  }

  @media (min-width: 768px) {
    .bd-placeholder-img-lg {
      font-size: 3.5rem;
    }
  }*/
</style>