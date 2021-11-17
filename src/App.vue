<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <img alt="JS logo" src="./assets/logojs.png" height="195" width="195">
    <HelloWorld msg="Aprendendo a mexer nessa bagaça"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
