<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Titolo />
  </div>
</template>

<script>
import Titolo from './components/Titolo.vue'

export default {
  name: 'App',
  components: {
    Titolo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
