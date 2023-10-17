<template>
    <div id="app">
    <NavBar/>
    <FotoP/>
    <InformacionPersonal/>
    <HabilidadesP/>    
    <ExperienciaLaboral/>
    <PiePagina/>
    <BtnArriba/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import FotoP from './components/FotoP.vue'
import InformacionPersonal from './components/InformacionPersonal.vue'
import HabilidadesP from './components/HabilidadesP.vue'
import ExperienciaLaboral from './components/ExperienciaLaboral.vue'
import PiePagina from './components/PiePagina.vue'
import BtnArriba from './components/BtnArriba.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    FotoP,
    InformacionPersonal,
    HabilidadesP,
    ExperienciaLaboral,
    PiePagina,
    BtnArriba,
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
  height: auto;
  scroll-margin-top:  10px;
  padding: 10px 20px;
  margin: 10px 20px;
}

h1 {
    font-size: 4rem;
    padding-bottom: 0%;
    margin-bottom: 0;
}

h2 {
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--accent-color);
}

h3 {
    font-size: 1.5rem;
    font-weight: 500;
}
</style>
