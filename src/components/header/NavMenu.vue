<template>
	<ul class="navbar-nav me-auto mb-2 mb-md-0">
    <li class="nav-item"><router-link to="/" class="nav-link px-2 text-secondary">Home</router-link></li>
    <li class="nav-item"><router-link to="/catalog" class="nav-link px-2 text-white">Catalog</router-link></li>
    <li class="nav-item"><router-link to="/about" class="nav-link px-2 text-white">About</router-link></li>
    <li class="nav-item"><router-link to="/blog" class="nav-link px-2 text-white">Blog</router-link></li>
  </ul>
</template>

<script>
  export default {
    name: 'NavMenu',
    components: {}
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
