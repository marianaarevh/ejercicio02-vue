<template>
  <header>

    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Sobre mi</a></li>
        <li><a href="#">Habilidades</a></li>
        <li><a href="#">Experiencias</a></li>
      </ul>
    </nav>


  </header>

</template>


<script>
    export default {
      name: 'NavBar',
    }
</script>


<style>

header{
    background-color: var(--dark-base-color);
    position: fixed;
    width: 100%;
    height: 70px;

    display: flex;
    align-items: center;
    top: 0;
    right: 0;
    left: 0;
    z-index:  2;

    justify-content: space-between;
}

nav {
    display: flex;
    align-items: center;
    right: 0;
    text-align: center;
 
}

nav ul{
    list-style: none;
    display: flex;

    padding: 0;
    margin: 0;
    
}

nav li {
    display: flex;
    padding: 0.3rem 1rem;
    
}

nav li a{
    text-decoration: none;
    padding: 25px;
    color: var(--base-color);
}

nav li:hover a{
    background-color: var(--accent-color);
}

</style>