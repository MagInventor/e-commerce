<template>
  <div class="text-end mb-4 mt-4 mb-md-0 mt-md-0 ms-2">
    <!-- <router-link to="/activation"> -->
      <button 
        type="button" 
        class="btn btn-outline-info me-2"
        @click="changeActivation(0)"
      >
        {{login}}
      </button>
    <!-- </router-link> -->
    <!-- <router-link to="/activation"> -->
      <button 
        type="button" 
        class="btn btn-outline-light"
        @click="changeActivation(1)"
      >
        {{signup}}
      </button>
    <!-- </router-link> -->
  </div>
</template>

<script>
  export default {
    name: 'ActivationButtons',
    components: {},
    data() {
      return {
        login: 'Login',
        signup: 'Sign-up'
      }
    },
    methods: {
      changeActivation(num) {
        document.querySelector('.modal').classList.add('d-block')

        document.querySelectorAll('.form-activation_registration').forEach(item => {
          if (num) {
            item.classList.add('form-activation_show')
          } else {
            item.classList.remove('form-activation_show')
          }
         
        })
      }
    }
  }
</script>
