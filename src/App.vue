<template>
  <div id="app">
      <navbar></navbar>
    <router-view/>
  </div>
</template>

<script>

import Navbar from './components/navbar/Navbar.vue'
import Login from './components/login/Login.vue'

export default {
  name: 'app',
  components: {
    Navbar,
    Login
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
