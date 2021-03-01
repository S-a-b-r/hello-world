<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <vMainWrapper/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import vMainWrapper from './components/v-main-wrapper'


export default {
  name: 'App',
  components: {
    HelloWorld,
    vMainWrapper
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
