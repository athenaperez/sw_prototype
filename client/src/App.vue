<template>
  <div id="app">
    <img alt="Society Wildlogo" src="./assets/sw18_logo_long_v2.png" id="header--img">
    <HelloWorld msg="Welcome to Society Wild"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
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

#header--img {
  max-width: 50%;
}

</style>
