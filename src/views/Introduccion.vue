<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .d-flex.justify-content-center.align-items-center.bg-verde.mb-4         
        .col-lg-4
          img(src="../assets/introduccion/ImgIntroduction.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-lg-8
          p Este componente ofrece una formación integral en la elaboración de conservas de frutas y verduras, con un enfoque en la inocuidad y la calidad del producto final. A lo largo del programa, el aprendiz adquirirá conocimientos sobre los principios fundamentales de conservación, los métodos de esterilización, y las mejores prácticas de higiene y manipulación de alimentos. Se profundizará en la composición de frutas y verduras, analizando las sustancias bioactivas y sus beneficios para la salud, y se abordarán los factores que afectan la calidad poscosecha, proporcionando herramientas para optimizar la duración de las conservas. Al finalizar, el aprendiz estará capacitado para seleccionar ingredientes de calidad y elaborar conservas de manera segura y eficiente.
    
    .justify-content-center.align-items-center           
      .col-lg-12
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/vdPrCjWJSHo?si=X4NxENRo3LLXAua_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.bg-verde
  background-color: #ABC093
  padding: 0px 20px
</style>
