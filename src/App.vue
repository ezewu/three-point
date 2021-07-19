<template>
  <div id="app">
    <Three />
  </div>
</template>

<script>
import Three from './components/three.vue'

export default {
  name: 'App',
  components: {
    Three
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
}
</style>
