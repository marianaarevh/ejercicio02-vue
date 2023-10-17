<template>
<section id="experiencias">
            <h1>Experiencia Laboral?</h1>
            <h2>ninguna... PERO si tengo experiencias académicas: </h2>
            <div class="contenedor-experiencias">
            <div class="main-pic card">
                <img src="../assets/img/investigacion.png" alt="Verano de Investigacion (Mariana A.)">
                <h3>Verano de investigación en Edo. Mexico</h3>
            </div>
                <div class="main-pic card">
                    <img src="../assets/img/new-mexico.jpg" alt="Internado (Mariana A.)">
                    <h3>Internado en Nuevo Mexico</h3>
                </div>
        </div>
        </section>
</template>


<script>
export default {
      name: 'ExperienciaLaboral',
    }
</script>


<style>
.card {
    position: flex;
    padding: 20px;
    margin: 20px;
    background: var(--base-color);
    box-shadow: 0px 1px 3px 0.1px var(--accent-color);
    border-radius: 10px;
    text-align: center;
    width: 35%;
    color: var(--accent-color);
    }


.contenedor-experiencias {
    display: flex;
  justify-content: space-evenly;
  align-items: center;
  text-align: center;   
}

.main-pic, .secondary-pic {
    padding: 20px;
}

.main-pic > img {
    width: 70%;
    padding: 0px;
    margin: 20px;
    border-radius: 7px;
        
}

</style>