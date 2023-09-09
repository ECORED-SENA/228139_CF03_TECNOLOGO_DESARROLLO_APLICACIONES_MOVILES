<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción


    p.mb-4(data-aos="fade") Aquí comienza el estudio del componente formativo #[strong “Validación de requisitos”]; explore la información del video que se muestra enseguida, la cual le contextualiza sobre los aspectos más importantes de los temas por desarrollar. #[strong ¡Adelante!]


    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/HEl0GrMFq88?si=vYUuM7k_uSET54z4" title="Validación de requisitos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video.Validación de requisitos


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
