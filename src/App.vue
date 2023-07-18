<template>
  <img alt="Vue logo" src="./assets/happy.png">
  <HelloWorld msg="Welcome to the cat App"/>
  <a href="https://www.flaticon.com/free-icons/cute" title="cute icons">Cute icons created by Freepik - Flaticon</a>
  <a href="https://www.flaticon.com/free-icons/cat" title="cat icons">Cat icons created by Smashicons - Flaticon</a>
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
