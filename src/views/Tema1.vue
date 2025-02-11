<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-botones
        .titulo-principal__numero
          span 1
        h1 Generalidades de las frutas y verduras
      
      p Este material de estudio te ayudará a comprender las características, beneficios y clasificación de las frutas y verduras, esenciales para una alimentación saludable y equilibrada. Aprenderás sobre sus propiedades nutricionales, su papel en la prevención de enfermedades y cómo incorporarlas de forma efectiva a tu dieta. En este componente se exponen los temas relacionados con las características, clasificación, propiedades y componentes de las frutas y verduras, además se describen las sustancias bioactivas (antioxidantes) y los mecanismos que alteran la calidad de estos alimentos.
      
      .row.mb-5
        .col-lg-5.my-3
          img(src="../assets/curso/temas/Tema1Img1.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-lg-7.d-flex.flex-column.justify-content-center
          img(src="../assets/curso/temas/titulo.png", alt="Imagen alineada izquierda" class="img-fluid")
          p Las frutas y verduras son alimentos esenciales que proporcionan numerosos beneficios para nuestra salud. Son ricas en vitaminas, minerales, fibra y antioxidantes que ayudan a mantener un cuerpo sano y a prevenir enfermedades.
          p Su alto contenido de fibra mejora la digestión, regula los niveles de colesterol y previene el estreñimiento. Las frutas y verduras también son bajas en calorías y ricas en agua, lo que las convierte en una opción ideal para controlar el peso y mantener una buena hidratación. 
          .cajon.color-acento-botones.p-4 Además, poseen antioxidantes que protegen nuestras células del daño causado por los radicales libres, ayudando a prevenir enfermedades como el cáncer y las enfermedades cardíacas. 
      
      .row
      div#t_13_1.titulo-segundo.color-acento-botones
        h2 1.1  Diferencia entre frutas y verduras

      p Las frutas y verduras son ambas partes comestibles de las plantas, pero se diferencian en su origen y función dentro del ciclo de vida de la planta. Las frutas se desarrollan a partir de la flor y contienen las semillas de la planta. Son los elementos reproductivos de las plantas denominados ovarios, estas contienen semillas en su interior y son de colores llamativos para atraer a los animales que después de comerlas expulsan las semillas al suelo en donde comienza nuevamente el ciclo reproductivo de la planta con su germinación.

      img(src="../assets/curso/temas/Tema1Img2.png", alt="Imagen alineada izquierda" class="img-fluid")

      .row.my-4
        .col-4.container-peach.p-5
          img(src="../assets/curso/temas/Tema1Img3.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-5.container-orange.flex-column.justify-content-center.d-flex
          p Su función es la de proteger y dispersar las semillas para la reproducción de la planta. Por lo general, son dulces o ácidas y tienen una textura jugosa. 
          p Las verduras, por otro lado, son otras partes de la planta, como las raíces, los tallos, las hojas y las flores. No tienen la función de reproducir la planta, pero aportan nutrientes esenciales para su crecimiento y desarrollo.
          p Aunque algunas frutas como los tomates, los pepinos o las calabazas se consumen como verduras, en realidad son frutos que se han adaptado para ser utilizados en platos salados. 
        .col-3
          img(src="../assets/curso/temas/Tema1Img4.png", alt="Imagen alineada izquierda" class="img-fluid")
      
      .row.my-4
        .col-4 
          img(src="../assets/curso/temas/titulo2.png", alt="Imagen alineada izquierda" class="img-fluid",)
      img(src="../assets/curso/temas/Tema1Img5.png", alt="Imagen alineada izquierda" class="img-fluid",)
      
      div.titulo-sexto.color-acento-botones.mb-3.my-3
        h5 Tabla 1.
        span Clasificación de las frutas.

      .row
        .tabla-a.color-acento-botones 
          table
            caption Nota. Sena (2024)
            thead
              tr
                th Clasificación
                th Descripcion
                th Ejemplos
            tbody
              tr
                td Tipo de semilla
                td
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Frutas de hueso: poseen una semilla dura y cubierta por una cáscara, como el melocotón, la ciruela o el albaricoque.
                    .fila(style="padding: 5px 0;")
                      p Frutas de pepitas: contienen numerosas semillas pequeñas, como la manzana, la pera, la granada, el kiwi, etc.
                    .fila(style="padding: 5px 0;")
                      p Frutas de grano: contienen pequeñas semillas diminutas, como las fresas, las frambuesas, las moras, etc.
                td
                  // Contenedor que divide la celda en tres filas
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Melocoton
                    .fila(style="padding: 5px 0;")
                      p Manzana
                    .fila(style="padding: 5px 0;")
                      p Fresa
                
              tr
                td Tiempo de recolección
                td
                  // Contenedor que divide la celda en tres filas
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Frutas frescas: corresponde a las frutas que están destinas para ser consumidas a los pocos días después de ser recolectadas. Se recolectan maduras y se consumen en fresco, como la fresa, la uva, el plátano, etc.
                    .fila(style="padding: 5px 0;")
                      p Frutas secas: son las frutas que se han sometido a un proceso de desecación, este consiste en deshidratar las frutas con el fin de que tengan un mayor tiempo de conservación, se elimina gran parte de su contenido de agua y de igual manera se disminuye su nivel de vitaminas.
                td
                  // Contenedor que divide la celda en tres filas
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Plátano, Banano.
                    .fila(style="padding: 5px 0;")
                      p Pasas, dátiles
              tr
                td Climatéricas (Esta es posiblemente la clasificación más relevante a la hora de determinar un sistema de cultivo y cosecha).
                td
                  // Contenedor que divide la celda en tres filas
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Frutas de hueso: poseen una semilla dura y cubierta por una cáscara, como el melocotón, la ciruela o el albaricoque.
                    .fila(style="padding: 5px 0;")
                      p Frutas de pepitas: contienen numerosas semillas pequeñas, como la manzana, la pera, la granada, el kiwi, etc.
                td
                  // Contenedor que divide la celda en tres filas
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p manzana, pera, plátano, ciruela, higo, melón, aguacate, kiwi, tomate, mango, chirimoya, melocotón, melón, membrillo, sandía, papaya, entre otras.
                    .fila(style="padding: 5px 0;")
                      p naranja, limón, cereza, frambuesa, uva, aceituna, pimiento, pepino, piña, mora, arándano, berenjena, pomelo, granada, calabaza, calabacín, lima, fresa, entre otros.
      
      .row.justify-content-center.mt-5
        .col-auto
          a.boton.color-acento-darkgreen.texto-blanco(
            href="https://ecored-atlantico.github.io/CATALAGO_BASE/downloads/Cajon.txt"
            target="_blank"
            type="application/pdf"
          )
            span Otras clasificaciones para las frutas son las siguientes:

        .row.d-flex.container-peach-2.my-3.p-2
          .col-4
            img(src="../assets/curso/temas/Tema1Img6.png", alt="Imagen alineada izquierda" class="img-fluid",)

          .col-8
            SlyderF(columnas="col-lg-6 col-xl-6")
              .tarjeta.tarjeta--blanca.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='../assets/curso/temas/Fruta1.png' alt='AvatarTop')
                h2.text-center Frutas cítricas
                p.text-centerson las que contienen ácido cítrico como el limón. 

              .tarjeta.tarjeta--blanca.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='../assets/curso/temas/Fruta2.png' alt='AvatarTop')
                h2.text-center Frutas tropicales
                p.text-center : son aquellas provenientes de climas tropicales y que deben mantenerse a temperaturas por encima de los 4 °C, de lo contrario pueden echarse a perder. 

              .tarjeta.tarjeta--blanca.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='../assets/curso/temas/Fruta3.png' alt='AvatarTop')
                h2.text-center Frutas del bosque
                p.text-center son las que crecen en zonas boscosas como por ejemplo las moras o las frambuesas.

              .tarjeta.tarjeta--blanca.p-4
                .row.justify-content-center.mb-3
                  .col-8
                    img(src='../assets/curso/temas/Fruta4.png' alt='AvatarTop')
                h2.text-center Frutos secos
                p.text-center correspondiente a las frutas que naturalmente tienen un nivel inferior al 50% de agua y son ricos en grasas y proteínas, por lo cual aportan mucha energía a quienes los consumen.
    
      .col-6.my-3
        img(src="../assets/curso/temas/titulo.png", alt="Imagen alineada izquierda" class="img-fluid")
      img(src="../assets/curso/temas/Banner4.png", alt="Imagen alineada izquierda" class="img-fluid")
      
      p.py-4 Se entiende por verduras aquellas partes comestibles de las plantas; la forma en que estas se clasifican está determinada según la parte de la planta a la que corresponden. A continuación, se encuentra un listado de las clasificaciones y su respectiva descripción:

      div.titulo-sexto.color-acento-botones.mb-3.my-3
        h5 Tabla 2.
        span Clasificación de verduras

      

  </template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
  }),
}
</script>

<style lang="sass">
.container-orange
  background-color: #FB9231
.container-peach
  background-color: #FFE8D2
.boton.color-acento-darkgreen
  background-color: #33490B
.container-peach-2
  background-color: #FFF0D6
</style>
