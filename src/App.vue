<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <BeerGrid msg="Welcome to The BeerHub App"/>
</template>

<script>
import BeerGrid from './components/BeerGrid.vue'

export default {
  name: 'App',
  components: {
    BeerGrid
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
