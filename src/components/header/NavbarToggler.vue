<template>
  <button 
    class="navbar-toggler" 
    type="button" 
    data-bs-toggle="collapse" 
    data-bs-target="#navbarCollapse" 
    aria-controls="navbarCollapse" 
    aria-expanded="false" 
    aria-label="Toggle navigation"
    @click="toggleMenu"
  >
    <span class="navbar-toggler-icon"></span>
  </button>
</template>

<script>
  export default {
    name: 'NavbarToggler',
    components: {},
    methods: {
      toggleMenu() {
        document.getElementById('navbarCollapse').classList.toggle('show')
      }
    }
  }
</script>

<style>
	nav a {
    font-weight: bold;
    color: #2c3e50;
  }

  nav a.router-link-exact-active {
    color: #42b983;
  }
</style>
