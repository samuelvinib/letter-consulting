<template>
  <div id="app">
    <MenuInicial/>
    <FooterPage/>
  </div>
</template>

<script>
import MenuInicial from './components/MenuInicial.vue'
import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    MenuInicial,
    FooterPage
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400&display=swap');
h1,h2,h3,h4,p,a{
  font-family: 'Lato', sans-serif;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
