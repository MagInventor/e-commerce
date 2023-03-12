<template>
  <div class="text-end mb-4 mt-4 mb-md-0 mt-md-0 ms-2">
    <router-link to="/activation">
      <button type="button" class="btn btn-outline-info me-2">Login</button>
    </router-link>
    <router-link to="/activation">
      <button type="button" class="btn btn-outline-light">Sign-up</button>
    </router-link>
  </div>
</template>

<script>
  export default {
    name: 'ActivationButtons',
    components: {}
  }
</script>
