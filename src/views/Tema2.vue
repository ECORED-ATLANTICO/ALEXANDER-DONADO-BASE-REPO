<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Importancia de las frutas y verduras
    
  
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        img(src="../assets/curso/temas/tema2/imgtema2.png", alt="Imagen alineada izquierda" class="img-fluid")
      .col-lg-8.
        p Las frutas y verduras son fundamentales en nuestra dieta y tienen un potente impacto en la salud humana, gracias a su contenido diverso y rico en compuestos bioactivos. Estas sustancias, conocidas como fitoquímicos, están presentes en los alimentos de origen vegetal e intervienen en múltiples procesos biológicos, ofreciendo beneficios que van más allá de la nutrición básica. A través de la investigación, se ha demostrado que estos compuestos pueden contribuir a la prevención de enfermedades, mejorar la salud cardiovascular y retrasar el envejecimiento. En este aparte, exploraremos las sustancias bioactivas, los esteroles vegetales y los mecanismos que afectan la calidad de las frutas y verduras, resaltando su papel crucial en la promoción del bienestar y la salud a lo largo de la vida. 
    
    

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
