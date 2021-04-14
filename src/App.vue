<template>
  <div id="app">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <router-link class="navbar-item" to="/">
         <h5><strong>Etoro Ekanem</strong></h5>
        </router-link>

        <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample" :class="{ 'is-active': showNav }" @click="showNav = !showNav">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu" :class="{ 'is-active': showNav }">
        <div class="navbar-start">

        </div>

        <div class="navbar-end">
          <router-link to="/" class="navbar-item">
            Home
          </router-link>
          <router-link to="/about" class="navbar-item">
           About
          </router-link>
          <router-link to="/projects" class="navbar-item">
           Projects
          </router-link>
          <router-link to="/contact" class="navbar-item">
           Contact
          </router-link>
       </div>
     </div>
   </nav>

   <router-view />
   <footer class="footer">
    <div class="content has-text-centered is-bold" >
        <strong>GAMBIT®</strong>
    </div>
  </footer>
</div>
</template>

<script>
  export default {
    name: "App",
    data() {
      return{
        showNav: false
      }
    },
  };
</script>

<style type="text/css">
#app {
  
  overflow: hidden;
  display: block;
  position: relative;
  padding-bottom: 150px; /* height of your footer */
}
footer {
 position: absolute;
 height: auto;
 bottom: 0;
 width: 100%;
 padding: 2rem 1rem 4rem !important;
 background-color: #293729
 
}

.navbar-item:hover{
  
color: #293729
}

</style>

<style lang="sass">

$primary: #293729

.hero-home
  @extend .hero

  background-image: url("./assets/archi.jpg");
  
  background-size: cover

@import "~bulma/bulma.sass"

</style>
