<template>
  <header>
    <nav class="navbar navbar-expand-md navbar-dark fixed-top text-bg-dark">
      <div class="container-fluid">
        <a class="logo navbar-brand" href="#">Robot</a>
        <navbar-toggler/>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <nav-menu/>
          
          <form-search/>

          <div class="text-end mb-4 mt-4 mb-md-0 mt-md-0 ms-2">
            <button type="button" class="btn btn-outline-info me-2">Login</button>
            <button type="button" class="btn btn-outline-light">Sign-up</button>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
import NavMenu from './NavMenu.vue'
import FormSearch from './FormSearch.vue'
import NavbarToggler from './NavbarToggler.vue'

  export default {
    name: 'HeaderComponent',
    components: {
      NavMenu, FormSearch, NavbarToggler
    }
  }
</script>

<style>
  .nav-scroller {
    position: relative;
    z-index: 2;
    height: 2.75rem;
    overflow-y: hidden;
  }

  .nav-scroller .nav {
    display: flex;
    flex-wrap: nowrap;
    padding-bottom: 1rem;
    margin-top: -1px;
    overflow-x: auto;
    text-align: center;
    white-space: nowrap;
    -webkit-overflow-scrolling: touch;
  }
</style>
