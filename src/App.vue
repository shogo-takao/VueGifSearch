<template>
  <div id="app">
    <vue-header></vue-header>
    <vue-list></vue-list>
  </div>
</template>

<script>
import VueHeader from './components/Header'
import VueList from './components/List'

export default {
  components: {
    VueHeader,
    VueList
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
