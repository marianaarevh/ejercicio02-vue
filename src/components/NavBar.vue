<template>
  <header>

    <nav>
      <ul>
        <li><a href="#inicio">Sobre mi</a></li>
        <li><a href="#sobre-mi">Sobre mi</a></li>
        <li><a href="#habilidades">Habilidades</a></li>
        <li><a href="#experiencias">Experiencias</a></li>
        <li><a href="#footer">Contacto</a></li>

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
    width: 99%;
    top: 10px;
    border-radius: 40px;
    align-items: center;

    z-index:  5;
}

nav {
    display: flex;
    align-items: center;
 
}

nav ul{
    list-style: none;
    display: flex;
    justify-content: space-between;
    padding: 0;
    margin: 0;
}

nav li {
    padding: 0.3rem 1rem;
    
}

nav li a{
    text-decoration: none;
    padding: 5px;
    color: var(--base-color);
    font-size: 1.2rem;
}

nav li:hover {
    background-color: var(--accent-color);
    border-radius: 20px;
}


</style>