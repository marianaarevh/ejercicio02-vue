<template>
    <div id="app">
    <NavBar/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style>
:root {
    --base-color: #FFFDF9;
    --dark-base-color: black;
    --accent-color: rgb(31, 86, 205); 
}
body{
  background-color: var(--base-color);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--dark-base-color);
  margin-top: 60px;
}
</style>
