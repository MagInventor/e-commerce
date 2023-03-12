<template>
	<form class="d-flex" role="search">
    <input type="search" class="form-control form-control-dark text-bg-dark" placeholder="Search..." aria-label="Search">
  </form>
</template>

<script>
  export default {
    name: 'FormSearch',
    components: {}
  }
</script>

<style>
	.form-control-dark {
    border-color: var(--bs-gray);
  }

  .form-control-dark:focus {
    border-color: #fff;
    box-shadow: 0 0 0 .25rem rgba(255, 255, 255, .25);
  }
</style>
