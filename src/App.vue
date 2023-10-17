<template>
    <div id="app">
    <NavBar/>
    <FotoP/>
    <PiePagina/>
    <BtnArriba/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import FotoP from './components/FotoP.vue'
import PiePagina from './components/PiePagina.vue'
import BtnArriba from './components/BtnArriba.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    FotoP,
    PiePagina,
    BtnArriba
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

section {
  height: 100vh;
}

h1 {
    font-size: 4rem;
    padding-bottom: 0%;
    margin-bottom: 0;
}

h3 {
    font-size: 2.5rem;
}
</style>
