<template>
    <section id="inicio">
        <h1>Mariana.</h1>
        <h2>estudiante de ingenieria en sistemas</h2>
        <img src="../assets/img/mariana.jpeg" alt="Mariana Arevalo" />
    </section>
</template>

<script>
export default {
  props: {
    imagenUrl: {
      type: String,
      required: true
    }
  }
};

</script>


<style>
#inicio {
    text-align: center;
}

#inicio > img {
    width: 300px;
    border-radius: 150px;
    box-shadow: 0px 0.5px 5px 1px var(--accent-color);
}

#inicio > img:hover {
    transform: scale(1.05);
}

</style>