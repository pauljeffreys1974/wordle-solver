<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <WordleSolve msg="Welcome to Your Vue.js App"/>
</template>

<script>
import WordleSolve from './components/WordleSolve.vue'

export default {
  name: 'App',
  components: {
    WordleSolve
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
  margin: 20px;
}
</style>
