<template>
  <nav class="navbar is-dark">
    <div class="navbar-brand">
      <a class="navbar-item" href="https://bulma.io">
        <img src="https://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
      </a>
      <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>

    <div id="navbarExampleTransparentExample" class="navbar-menu">
      <div class="navbar-start">
        <router-link to="home" class="navbar-item" >
          Home
        </router-link>
       <!-- <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link" href="/home">
            Home
          </a>
          <div class="navbar-dropdown is-boxed">
            <a class="navbar-item" href="/documentation/overview/start/">
              Overview
            </a>
            <a class="navbar-item" href="https://bulma.io/documentation/modifiers/syntax/">
              Modifiers
            </a>
            <a class="navbar-item" href="https://bulma.io/documentation/columns/basics/">
              Columns
            </a>
            <a class="navbar-item" href="https://bulma.io/documentation/layout/container/">
              Layout
            </a>
            <a class="navbar-item" href="https://bulma.io/documentation/form/general/">
              Form
            </a>
            <hr class="navbar-divider">
            <a class="navbar-item" href="https://bulma.io/documentation/elements/box/">
              Elements
            </a>
            <a class="navbar-item is-active" href="https://bulma.io/documentation/components/breadcrumb/">
              Components
            </a>
          </div>
        </div>-->
      </div>
    </div>
  </nav>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'app'
})
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
