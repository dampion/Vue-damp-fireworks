<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Fireworks</h1>
    <Firework :boxHeight="'100%'" :boxWidth="'100%'"/>
  </div>
</template>

<script>
import Firework from './components/fireworks.vue'

export default {
  name: 'app',
  components: {
    Firework
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
