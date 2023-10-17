<template>
    <section id="habilidades">
            <h1>Habilidades</h1>
            <div class="contenedor-skills">
            <div class="skills">
                <h3>Hard skills</h3>
                <ul>
                    <li v-for="hardskill in hardskills" :key="hardskill">
                         {{ hardskill }}
                    </li>
                </ul>
            </div>

            <div class="skills">
                <h3>Soft skills</h3>
                <ul>
                    <li v-for="softskill in softskills" :key="softskill">
                         {{ softskill }}
                    </li>
                </ul>
                
            </div>

            <div class="skills">
                <h3>Idiomas</h3>
                <ul>
                    <li v-for="idioma in idiomas" :key="idioma">
                         {{ idioma }}
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>


<script>
 export default {
    data() {
      return {
        hardskills: [
          'Python',
          'Github',
          'HTML'
        ],
        softskills: [
          'Autoaprendizaje',
          'Esfuerzo',
          'Empatía'
        ],
        idiomas: [
          'Español',
          'Ingles',
          'Aleman'
        ]
      };
    }
  };
</script>


<style>
#habilidades {
    background-color: var(--accent-color);
    margin: 0;

}

.contenedor-skills {
    margin: 0;
    display: flex;
    /*grid-template-columns: 1.5fr 1fr 1fr 1fr; */
    grid-gap: 30px;
    padding: 60px;
}

#habilidades h1 {
    color: var(--base-color);
    
}

.skills {
    background-color: var(--base-color);
    border-radius: 400px;
    text-align: center;
    align-items: center;
    width: 80%;
    height:auto;
    padding: 15px 10px;
    margin: 5px;
}

.skills:hover{
    transform: scale(1.1);
}

.skills h3{
    color: var(--accent-color);
    font-weight: 600;
}

.skills h3 p{
    padding: 0;
    margin: 0px;
}

ul{
    list-style: none;
    padding: 0px;
    margin: 0px;
}
</style>