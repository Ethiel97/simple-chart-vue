<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="Simple data visualization with Vue.js and Chart.js"/>
    <visualisation></visualisation>

  </div>
</template>

<script>
/* eslint-disable */

import Visualisation from './components/Visualisation.vue';
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    Visualisation,
    HelloWorld
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
