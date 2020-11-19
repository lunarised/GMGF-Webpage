<template>
  <NavBar/>
  <Home/>
</template>

<script>
import NavBar from './components/NavBar'
import Home from './pages/home.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #dddddd;
  //margin-top: 60px;
  margin: 0px, 0px, 0px, 0px;
  padding: 0px, 0px, 0px, 0px;
}
body{
  margin: 0;
  background-color: #222222;
}
</style>
