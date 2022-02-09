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