<template>
  <header>
    <nav class="navbar navbar-expand-md navbar-dark fixed-top text-bg-dark">
      <div class="container-fluid">
        <a href="#" class="logo navbar-brand">Robot</a>
        <navbar-toggler/>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <nav-menu/>
          <form-search/>
          <activation-buttons/>
        </div>
      </div>
    </nav>
    <form-activation/>
  </header>
</template>

<script>
import NavMenu from './NavMenu.vue'
import FormSearch from './FormSearch.vue'
import NavbarToggler from './NavbarToggler.vue'
import ActivationButtons from './ActivationButtons.vue'
import FormActivation from '../forms/FormActivation.vue'

  export default {
    name: 'HeaderComponent',
    components: {
      NavMenu, 
      FormSearch, 
      NavbarToggler, 
      ActivationButtons,
      FormActivation
    }
  }
</script>

<style>
  .logo {
    color: #fff;
  }

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
