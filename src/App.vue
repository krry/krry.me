<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Faves msg="Welcome to me krry"/>
  </div>
</template>

<script>
import Faves from './components/Faves.vue'

export default {
  name: 'app',
  components: {
    Faves
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
