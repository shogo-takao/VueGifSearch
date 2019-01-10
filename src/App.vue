<template>
  <div id="app">
    <vue-header></vue-header>
  </div>
</template>

<script>
import VueHeader from './components/Header'

export default {
  components: {
    VueHeader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
