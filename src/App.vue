<template>
  <div id="app">
    <!-- Questo è il componente Site Header -->
    <SiteHeader />
    <!-- Questo è il componente Site Main -->
    <SiteMain />
    <!-- Questo è il componente Site footer -->
    <SiteFooter />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import SiteHeader from '@/components/HeaderComponent.vue';
import SiteFooter from '@/components/FooterComponent.vue';
import SiteMain from '@/components/MainComponent.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld
    SiteHeader,
    SiteFooter,
    SiteMain
  },
}
</script>

<style lang="scss">
// Regola generale
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

// Div principale
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

/* Classi utilities */
.text_center {
  text-align: center;
}

img {
  max-width: 100%;
}

// Main
main {
  background-image: url('@/assets/img/fondo-pag-speciali.jpg');
  min-height: 50vh;
  background-size: cover;
  padding-bottom: 2rem;
  // H1 dentro al main
  h1 {
    padding: 2rem 0;
    text-align: center;
  }
}

// Import dal file di Sass
// La cartella si chiama sass, ma il file ha estensione scss
// attenzione
@import '@/assets/sass/grid_sistem';


</style>
