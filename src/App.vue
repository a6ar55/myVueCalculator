<template>
<my-calculator></my-calculator>
</template>

<script>
import MyCalculator from './components/MyCalculator.vue'

export default {
  name: 'App',
  components: {
    MyCalculator
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
