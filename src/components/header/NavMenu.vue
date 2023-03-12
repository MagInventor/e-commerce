<template>
	<ul class="navbar-nav me-auto mb-2 mb-md-0">
    <li class="nav-item"><router-link to="/" class="nav-link px-2">Home</router-link></li>
    <li class="nav-item"><router-link to="/catalog" class="nav-link px-2">Catalog</router-link></li>
    <li class="nav-item"><router-link to="/about" class="nav-link px-2">About</router-link></li>
    <li class="nav-item"><router-link to="/blog" class="nav-link px-2">Blog</router-link></li>
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
    color: #fff;
  }

  nav a.router-link-exact-active {
    color: #42b983;
  }

  nav a:hover {
    color: #ffc18e;
  }
</style>
