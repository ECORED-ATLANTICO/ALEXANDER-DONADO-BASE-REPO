<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 2
        h1 Importancia de las frutas y verduras
      .d-flex.row
        .col-lg-4
          figure
            img.mb-5(src="../assets/curso/temas/Tema1Img10.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-lg-8.p-2
          p.mb-0 Las frutas y verduras son fundamentales en nuestra dieta y tienen un potente impacto en la salud humana, gracias a su contenido diverso y rico en compuestos bioactivos. Estas sustancias, conocidas como fitoquímicos, están presentes en los alimentos de origen vegetal e intervienen en múltiples procesos biológicos, ofreciendo beneficios que van más allá de la nutrición básica. A través de la investigación, se ha demostrado que estos compuestos pueden contribuir a la prevención de enfermedades, mejorar la salud cardiovascular y retrasar el envejecimiento. En este aparte, exploraremos las sustancias bioactivas, los esteroles vegetales y los mecanismos que afectan la calidad de las frutas y verduras, resaltando su papel crucial en la promoción del bienestar y la salud a lo largo de la vida.
      span.title-with-decoration.mb-5.col-sm-12 Sustancias bioactivas
      p.mb-5 Las sustancias bioactivas también llamadas fitoquímicos corresponden a una serie de compuestos que están presentes en los alimentos de origen vegetal, tales como las frutas y verduras. Se denominan sustancias bioactivas pues tienen actividad biológica, sin embargo no son nutrientes esenciales para la vida, aun así tiene efectos positivos en la salud de las personas.
      .row.mb-5
        .col-lg-7.mb-3.mb-lg-0
          .cajon.color-acento-contenido.p-4 
            p.mb-0 El área de los fitoquímicos ha sido fuertemente estudiada en las últimas décadas, pues se ha encontrado que en el largo plazo tienen efectos muy positivos para las personas que las consumen, puesto que descontaminan el cuerpo de la presencia de drogas y toxinas, pueden prevenir el cáncer, neutralizan los radicales libre, mejoran la presión sanguínea y la coagulación de la sangre; por lo cual brindan protección contra enfermedades cardiovasculares. Otros beneficios que se han encontrado es que tienen algunas propiedades que retrasan los signos del envejecimiento y disminuye la probabilidad de adquirir enfermedades asociadas a la vejez.
        .col-lg-5.mb-3.mb-lg-0 
          figure
            img.mb-5(src="../assets/curso/temas/Tema1Img11.png", alt="Imagen alineada izquierda" class="img-fluid")
      .row.mb-5
        .col-lg-1.mb-3.mb-lg-0 
        .col-lg-3.mb-3.mb-lg-0 
        p.mb-0 Un ejemplo de las diferentes sustancias bioactivas son los pigmentos de las frutas y verduras en el que se encuentran las siguientes clasificaciones:
      .row.mb-5
        .col-lg-1.mb-3.mb-lg-0 
        .col-lg-3.mb-3.mb-lg-0 
          .tarjeta.tarjeta-slide.arriba.color-primario(@mouseover="indicadorTarjetaSlide = false")
            .indicador--hover(v-if="indicadorTarjetaSlide")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/Tema2/Img1.png')})`}")
              .tarjeta-slide__contenido.p-4.p-xl-6
                h1 Terpenos:
                p.texto-deslizable cumplen una función antioxidante, en este grupo están los pigmentos carotenoides. 
        .col-lg-3.mb-3.mb-lg-0 
          .tarjeta.tarjeta-slide.arriba.color-primario(@mouseover="indicadorTarjetaSlide = false")
            .indicador--hover(v-if="indicadorTarjetaSlide")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/Tema2/Img2.png')})`}")
              .tarjeta-slide__contenido.p-4.p-xl-5
                h1 Fenoles: 
                p.texto-deslizable desempeñan una función antioxidante, entre estos se encuentran a los pigmentos flavonoides presentes en los frutos azulados. 
        .col-lg-3.mb-3.mb-lg-0 
          .tarjeta.tarjeta-slide.arriba.color-primario(@mouseover="indicadorTarjetaSlide = false")
            .indicador--hover(v-if="indicadorTarjetaSlide")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/Tema2/Img3.png')})`}")
              .tarjeta-slide__contenido.p-4.p-xl-5
                h1 Tioles y lignanos: 
                p.texto-deslizable efectúan una función antioxidante y se pueden encontrarse en alimentos como el brócoli, el repollo, la cebolla, el trigo y la cebada.
      .tarjeta.tarjeta--azul.p-4
        SlyderA(tipo="b")
          .row
            .col-md-6.mb-4.mb-md-0
              p This is another paragraph...
            .col-md-6
              figure
                img(src='@/assets/curso/temas/Tema1Img10.png', alt='Texto que describa la imagen')
                figcaption Leyenda de la imagen
          .row.justify-content-center.align-items-center.my-lg-4
            .col-md-6
              figure
                img(src='@/assets/curso/temas/Tema1Img10.png', alt='Texto que describa la imagen')
                figcaption Leyenda de la imagen
            .col-md-6.mb-4.mb-md-0
              p This is another paragraph...
          div
            figure
              img(src='@/assets/curso/temas/Tema1Img10.png', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen
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
