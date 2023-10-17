<template>
<section id="sobre-mi">
            <h1>Sobre mí</h1>
            <h3>Soy estudiante de Ingeniería en Sistemas de Información, estoy cursando el séptimo semestre y tengo interés 
                en el área de testing y ciberseguridad. Mi mayor fortaleza es la capacidad para aprender y para trabajar
                 en equipo. Estoy en busca de ampliar mis conocimientos y crecer profesionalmente</h3>
        </section>
</template>


<script>
    export default {
      name: 'InformacionPersonal',
    }
</script>


<style>
#sobre-mi {
    display: grid;
    grid-template-columns: 0.5fr 1fr;
    grid-gap: 30px;
    padding-top: 60px;
    padding-bottom: 60px;
    padding: 60px;
    background-color: var(--base-color);
    margin: 10px 0px;
}

#sobre-mi h1{
    text-align: left;
    color: var(--accent-color);
}

#sobre-mi h3{
    text-align: left;
}


</style>
  