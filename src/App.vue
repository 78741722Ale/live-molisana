<template>
  <div id="app">
    <!-- Questo è il componente Site Header -->
    <SiteHeader />
    <!-- Main -->
    <main>
      <h1>Lista Prodotti</h1>
    </main>
    <!-- Questo è il componente Site footer -->
    <SiteFooter />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import SiteHeader from '@/components/HeaderComponent.vue';
import SiteFooter from '@/components/FooterComponent.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld
    SiteHeader,
    SiteFooter
  }
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

// Main
main {
  background-image: url('@/assets/img/fondo-pag-speciali.jpg');
  min-height: 50vh;
  background-size: cover;
}

// Grid Sistem per il footer
.container {
  margin: auto;
  max-width: 1440px;
}
.row {
  display: flex;
  flex-wrap: wrap;
}
.col {
  flex-grow: 1;
}

</style>
