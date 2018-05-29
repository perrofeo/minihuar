<template>
  <div>
    <nav class="navbar header has-shadow is-fixed-top" role="navigation" aria-label="main navigation">
      <div class="container">
      <div class="navbar-brand">
        <a class="navbar-item is-size-3-tablet has-text-weight-bold" href="/">
          abarketa
        </a>

        <div class="navbar-burger" v-on:click="showNav = !showNav" v-bind:class="{ 'is-active' : showNav }" data-target="navbarExampleTransparentExample">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
    
    <div id="navbarExampleTransparentExample" class="navbar-menu" v-bind:class="{ 'is-active' : showNav }">
    <div class="navbar-start">
      
    </div>

    <div class="navbar-end">
      <a class="navbar-item" href="https://bulma.io/">
        instagram
      </a>
      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link" href="/documentation/overview/start/">
          Docs
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
      </div>
      <div class="navbar-item">
        <div class="field is-grouped">
          <p class="control">
            <a href="#" class="snipcart-checkout button badge is-badge-outlined" data-badge="1">
              <span class="icon">
                <i class="material-icons">shopping_cart</i>
              </span>
            </a>
          </p>
          
        </div>
      </div>
    </div>
  </div>
      </div>
    </nav>
    <div>
       <nuxt />
    </div>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
    <script src="https://cdn.snipcart.com/scripts/2.0/snipcart.js" id="snipcart" data-api-key="YzViMTVmZWMtOTQ1My00MTYxLTkxNzgtZmUyNmRkZjE3OTM4NjM2NjMyMjE0OTE3MDA1MjMx"></script>   
  </div>
</template>

<script>
export default {
  data() {
    return {
      showNav: false
    }
  }
}
</script>

<style>
 

</style>
