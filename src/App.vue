<template>
  <SplashPage />
</template>

<script>
import SplashPage from './components/SplashPage.vue'

export default {
  name: 'App',
  components: {
    SplashPage
  }
}
</script>

<style>
html, body {
    background-color: #f1b0cf;
    margin: 0;
    padding: 0;
}
#app {
  /*font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;*/
  text-align: center;
}
</style>
