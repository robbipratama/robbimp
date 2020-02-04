<template>
  <div id="app">
    <h1>KALKULATOR</h1>
    <kalkulator/>
  </div>
</template>

<script>
import kalkulator from './components/kalkulator.vue'

export default {
  name: 'app',
  components: {
    kalkulator
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
