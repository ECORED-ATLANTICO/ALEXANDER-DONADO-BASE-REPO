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
        .col-lg-5.mb-3.mb-lg-0
          img(src="../assets/curso/temas/Tema1Img1.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-lg-7.d-flex.flex-column.justify-content-center
          span.title-with-decoration.mb-3 Importancia de las frutas y verduras para la salud
          p Las frutas y verduras son alimentos esenciales que proporcionan numerosos beneficios para nuestra salud. Son ricas en vitaminas, minerales, fibra y antioxidantes que ayudan a mantener un cuerpo sano y a prevenir enfermedades.
          p Su alto contenido de fibra mejora la digestión, regula los niveles de colesterol y previene el estreñimiento. Las frutas y verduras también son bajas en calorías y ricas en agua, lo que las convierte en una opción ideal para controlar el peso y mantener una buena hidratación. 
          .cajon.color-secundario.p-4 
            p.mb-0 Además, poseen antioxidantes que protegen nuestras células del daño causado por los radicales libres, ayudando a prevenir enfermedades como el cáncer y las enfermedades cardíacas. 
      
      div#t_13_1.titulo-segundo.color-acento-botones
        h2 1.1  Diferencia entre frutas y verduras
      p Las frutas y verduras son ambas partes comestibles de las plantas, pero se diferencian en su origen y función dentro del ciclo de vida de la planta. Las frutas se desarrollan a partir de la flor y contienen las semillas de la planta. Son los elementos reproductivos de las plantas denominados ovarios, estas contienen semillas en su interior y son de colores llamativos para atraer a los animales que después de comerlas expulsan las semillas al suelo en donde comienza nuevamente el ciclo reproductivo de la planta con su germinación.

      div.position-relative
        img(
          src="../assets/curso/temas/tema1/backgroundYellow.png", 
          alt="Fondo", 
          class="position-absolute bottom-0 start-50 translate-middle-x", 
          style="min-width: calc(100vw - 4em);"
        )
        .container-fluid.mb-5
          .row.justify-content-center
            .col-10
              img(
                src="../assets/curso/temas/tema1/polinizacion.png", 
                alt="Polinización", 
                class="img-fluid d-block mx-auto"
              )

      .row.mb-5.col-sm-12.justify-content-center
        .col-lg-4.container-peach.p-5
          img(src="../assets/curso/temas/Tema1Img3.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-lg-5.container-orange.d-flex.flex-column.justify-content-center
          p Su función es la de proteger y dispersar las semillas para la reproducción de la planta. Por lo general, son dulces o ácidas y tienen una textura jugosa. 
          p Las verduras, por otro lado, son otras partes de la planta, como las raíces, los tallos, las hojas y las flores. No tienen la función de reproducir la planta, pero aportan nutrientes esenciales para su crecimiento y desarrollo.
          p.mb-0 Aunque algunas frutas como los tomates, los pepinos o las calabazas se consumen como verduras, en realidad son frutos que se han adaptado para ser utilizados en platos salados. 
        .col-lg-3.d-flex.align-items-center.col-sm-8
          figure
            img(src="../assets/curso/temas/Tema1Img4.png", alt="Imagen alineada izquierda" class="img-fluid")
      
      
      
      .row.mb-5
          span.title-with-decoration.mb-5 Importancia de las frutas y verduras para la salud
          .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/temas/Tema1Img5.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 Existen diferentes tipos de frutas y todas se diferencian por sus colores, formas y sabores, esta gran variedad se clasifica de diferentes maneras según las características de las frutas de la siguiente manera:
      
      div.titulo-sexto.color-acento-botones.mb-5
        h5 Tabla 1.
        span Clasificación de las frutas

      .row
        .tabla-a.color-acento-botones.col-lg-10.mx-auto.mb-5
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
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Frutas frescas: corresponde a las frutas que están destinas para ser consumidas a los pocos días después de ser recolectadas. Se recolectan maduras y se consumen en fresco, como la fresa, la uva, el plátano, etc.
                    .fila(style="padding: 5px 0;")
                      p Frutas secas: son las frutas que se han sometido a un proceso de desecación, este consiste en deshidratar las frutas con el fin de que tengan un mayor tiempo de conservación, se elimina gran parte de su contenido de agua y de igual manera se disminuye su nivel de vitaminas.
                td
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Plátano, Banano.
                    .fila(style="padding: 5px 0;")
                      p Pasas, dátiles
              tr
                td Climatéricas (Esta es posiblemente la clasificación más relevante a la hora de determinar un sistema de cultivo y cosecha).
                td
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p Frutas de hueso: poseen una semilla dura y cubierta por una cáscara, como el melocotón, la ciruela o el albaricoque.
                    .fila(style="padding: 5px 0;")
                      p Frutas de pepitas: contienen numerosas semillas pequeñas, como la manzana, la pera, la granada, el kiwi, etc.
                td
                  .descripcion-container(style="display: flex; flex-direction: column;")
                    .fila(style="padding: 5px 0;")
                      p manzana, pera, plátano, ciruela, higo, melón, aguacate, kiwi, tomate, mango, chirimoya, melocotón, melón, membrillo, sandía, papaya, entre otras.
                    .fila(style="padding: 5px 0;")
                      p naranja, limón, cereza, frambuesa, uva, aceituna, pimiento, pepino, piña, mora, arándano, berenjena, pomelo, granada, calabaza, calabacín, lima, fresa, entre otros.
      
        span.color-acento-darkgreen.mx-auto.col-lg-5.mb-5.text-center Otras clasificaciones para las frutas son las siguientes 
 
        .row.d-flex.container-peach-2.mb-5.p-2
          .col-lg-4.col-md-8.align-self-center
            img(src="../assets/curso/temas/Tema1Img6.png", alt="Imagen alineada izquierda" class="img-fluid",)
          .col-lg-8.d-flex.align-items-center
            SlyderF(columnas="col-lg-6 col-xl-6 col-md-6")
              .tarjeta.tarjeta--blanca.p-2
                .d-flex.justify-content-center.mb-3
                  img(src='../assets/curso/temas/Fruta1.png' alt='naranja' style="width:72px")
                h4.text-center Frutas cítricas
                p.text-center.mb-0 Son las que contienen ácido cítrico como el limón. 

              .tarjeta.tarjeta--blanca.p-4
                .d-flex.justify-content-center.mb-3
                    img(src='../assets/curso/temas/Fruta2.png' alt='frutas tropicales' style="width:72px")
                h4.text-center Frutas tropicales
                p.text-center.mb-0 Son aquellas provenientes de climas tropicales y que deben mantenerse a temperaturas por encima de los 4 °C, de lo contrario pueden echarse a perder. 

              .tarjeta.tarjeta--blanca.p-4
                .d-flex.justify-content-center.mb-3
                    img(src='../assets/curso/temas/Fruta3.png' alt='frutas del bosque' style="width:72px")
                h4.text-center Frutas del bosque
                p.text-center.mb-0 Son las que crecen en zonas boscosas como por ejemplo las moras o las frambuesas.

              .tarjeta.tarjeta--blanca.p-4
                .d-flex.justify-content-center.mb-3
                    img(src='../assets/curso/temas/Fruta4.png' alt='frutos secos' style="width:72px")
                h4.text-center Frutos secos
                p.text-center.mb-0 Correspondiente a las frutas que naturalmente tienen un nivel inferior al 50% de agua y son ricos en grasas y proteínas, por lo cual aportan mucha energía a quienes los consumen.
    
      .col-lg-6
        span.title-with-decoration Clasificación de verduras
      img.mb-5(src="../assets/curso/temas/Banner4.png", alt="Imagen alineada izquierda" class="img-fluid")
      p.mb-5 Se entiende por verduras aquellas partes comestibles de las plantas; la forma en que estas se clasifican está determinada según la parte de la planta a la que corresponden. A continuación, se encuentra un listado de las clasificaciones y su respectiva descripción:
      div.titulo-sexto.color-acento-botones.mb-5
        h5 Tabla 2.
        span Clasificación de verduras

      .tabla-a.color-acento-botones.mb-5.col-lg-10.mx-auto
        table
          caption Nota. Sena (2024)
          thead
            tr
              th Clasificación
              th Descripción
              th Ejemplos
          tbody
            tr
              td Hoja
              td Se conocen como las verduras cuyas hojas son comestibles.
              td Lechuga, espinaca, col rizada.
            tr
              td Raiz
              td Corresponden a la parte de la planta que crece bajo la tierra y que se puede comer, por lo general son ricas en carbohidratos y azúcares
              td Zanahoria, remolacha, nabo.
            tr
              td Tallo
              td Estos se componen por el tallo y la raíz de la planta.
              td Apio, espárrago.
            tr
              td Flor
              td Son aquellas que se consumen principalmente por sus flores, que son la parte de la planta que se desarrolla antes de ser fertilizada.
              td Coliflor, brócoli, alcachofa.
            tr
              td Bulbo
              td Se estos hacen parte de ciertas plantas y se conforman por un tallo cubierto por escamas comestibles.
              td Cebolla, ajo.
            tr
              td Fruto
              td Aunque se consumen como verduras, en realidad son frutos que se han adaptado para ser utilizados en platos salados.
              td Tomate, pepino, calabaza.
            tr
              td Túberculo
              td Corresponden a la parte de la planta que cumple la función de reservar temporalmente las sustancias que esta necesita para su supervivencia tales como nutrientes y carbohidratos.
              td Papa, camote.

      span.title-with-decoration.mb-3.col-sm-12 Componentes de las frutas y verduras
      .d-flex.row
        .col-lg-5
          figure
            img.mb-5(src="../assets/curso/temas/Tema1Img7.png", alt="Imagen alineada izquierda" class="img-fluid")
        .col-lg-7.p-2
          p.mb-0 La composición de las frutas y las verduras varía según la clasificación a la que corresponden y el grado de maduración en que se encuentran. Pero a manera general, se puede decir que ambos están compuestos de una serie de elementos básicos que se encuentran en la extensa mayoría de frutas y verduras. A continuación se describen los componentes más importantes que se pueden encontrar tanto en frutas como en las verduras.

      div.d-flex.row
        div.col-lg-9
          AcordionA(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
            .row(titulo="Agua")
              .col-md-12.mb-4.mb-md-0
                p.mb-0 Las frutas y verduras por regla general se componen principalmente por agua, para el caso de las frutas sus niveles oscilan generalmente entre 50 % y 90 %, en las verduras los niveles están entre 75 % y 90 %. El agua proporciona la posibilidad a las frutas y verduras de mantenerse frescas e incluso poseer aromas, también influye directamente en su conservación porque aporta componentes a las células.
            .row(titulo="Carbohidratos")
              .col-md-12.mb-4.mb-md-0
                p Los carbohidratos representan entre el 5 % y 30 % de las frutas y verduras a modo general, pero naturalmente los valores varían dependiendo de cada caso específico de fruta o verdura. Los carbohidratos corresponden a los azúcares que dan la energía a quienes consumen los alimentos y son una parte esencial de la dieta del ser humano.
       
            .row(titulo="Fibras")
              .col-md-12.mb-4.mb-md-0
                p.mb-0 Fibra soluble: Retiene agua y se convierte en gel durante la digestión, lo que retrasa el proceso digestivo y permite una mejor absorción de nutrientes. También ayuda a reducir los niveles de colesterol en la sangre y regula el pH. Un tipo común de fibra soluble es la pectina, que se encuentra en frutas y verduras.
                hr
                p.mb-0 Fibra insoluble: Es la más abundante en los alimentos y acelera el tránsito intestinal, actuando como un laxante. Aumenta el peso de la materia fecal en el intestino. La fibra dietética tiene una gran capacidad de absorción de agua y es resistente a la digestión. Aunque no aporta valor nutricional directo, es crucial para la adecuada función de las contracciones musculares en los intestinos.
            .row(titulo="Proteínas")
              .col-md-12.mb-4.mb-md-0
                p Las frutas y verduras también poseen proteínas dentro de su composición química, sin embargo su contenido es inferior al 1%, así que no son consideradas como una fuente rica de estas. Las proteínas son compuestos orgánicos a base de carbono y otros elementos como el hidrógeno, el nitrógeno y el oxígeno.
        div.col-lg-3.col-md-8
          img.mb-5(src="../assets/curso/temas/Tema1Img8.png", alt="Imagen alineada izquierda" class="img-fluid")
        
      .row.flex-row-reverse
        .col-lg-9
          AcordionA(tipo="a" clase-tarjeta="tarjeta color-acento-contenido")
            .row(titulo="Pigmentos")
              .col-md-12.mb-4.mb-md-0
                p.mb-0 Un componente encontrado en frutas y verduras son los pigmentos, estos son las sustancias encargadas de darle el color a las frutas y verduras. La concentración de pigmentos varía con el tiempo de vida de la planta, a medida que esta avanza a través de las etapas de maduración. Existen tres tipos relevantes de pigmentos en las frutas y verduras: la clorofila, los carotenoides y los flavonoides.
            .row(titulo="Vitaminas")
              .col-md-12.mb-4.mb-md-0
                p Las vitaminas son sustancias que el cuerpo necesita para funcionar apropiadamente, sin embargo no tiene la capacidad de sintetizarlas por sí mismo, por lo tanto necesita de fuentes externas para poder obtenerlas. Las frutas y verduras son una buena fuente de vitaminas, en ellas se encuentra una variedad de estas sustancias que cumplen diversas funciones en el cuerpo humano tales como: prevenir enfermedades y deficiencias corporales, también sirven para efectuar diferentes reacciones metabólicas del organismo.
            .row(titulo="Minerales")
              .col-md-12.mb-4.mb-md-0
                p.mb-0 Los minerales son nutrientes inorgánicos muy importantes para los sistemas del cuerpo humano, hacen parte de los órganos y elementos internos de este. Se adquieren a través de la ingesta de una gran serie de alimentos como las frutas y verduras.
        .col-lg-3.col-md-8
            img.mb-5(src="../assets/curso/temas/Tema1Img9.png", alt="Imagen alineada izquierda" class="img-fluid")
    
      span.title-with-decoration.mb-5.col-sm-12 Importancia de las Vitaminas

      div.position-relative
        // Contenido principal
        div.row.d-flex.mb-5
          .col-lg-4.mb-lg-0.mb-3
            img(
              src="../assets/curso/temas/Tema1Img10.png", 
              alt="Imagen", 
              class="img-fluid"
            )
          .col-lg-8
            p Las frutas y verduras son una buena fuente de vitaminas, en ellas se encuentra una variedad de estas sustancias que cumplen diversas funciones en el cuerpo humano tales como: prevenir enfermedades y deficiencias corporales, también sirven para efectuar diferentes reacciones metabólicas del organismo.
            p.mb-0 Entre las vitaminas más importantes está la vitamina C, esta se encuentra contenida de manera natural en la mayoría de las frutas y verduras, especialmente aquellas del grupo de los cítricos. Después están las vitaminas del complejo B, que corresponden a un grupo de vitaminas diferentes que desempeñan importantes funciones del cuerpo desde complementar los ácidos nucleicos, desintoxicar el organismo, participar en las reacciones que generan energía, sintetizar proteínas, grasas y carbohidratos, entre otras.

        // Imagen de fondo
        img(
          src="../assets/curso/temas/backgroundOrange.svg", 
          alt="Fondo", 
          class="position-absolute bottom-0 start-50 translate-middle-x", 
          style="min-width: calc(100vw - 4em); z-index: -1;"
        )

      .cajon.color-secundario.p-4.col-lg-12.mb-5
        p.mb-0 También está la vitamina A, que es la que se encarga de generar pigmentos que la retina ocular de las personas necesita para funcionar adecuadamente, por lo cual es de gran importancia para tener una buena visión; esa vitamina se encuentra en alimentos como las zanahorias, el mango y la lechuga. Finamente está la vitamina E presente en vegetales de hoja verde tales como: las espinacas y el brócoli; esta vitamina es de un gran beneficio para el sistema circulatorio y adicional a eso tiene propiedades antioxidantes que ayudan a la prevención de algunas enfermedades como el párkinson. 
      
      div.mb-3.col-lg-8.mx-auto.d-block.mb-5
        div.titulo-sexto.color-acento-botones
          h5 Gráfico 1.
          span Vitaminas en las frutas y verduras.

        img.img-fluid.mb-3(
          src="../assets/curso/temas/Tema1Img11.svg", 
          alt="Fondo"
        )
        table
          caption Nota. Sena (2024)

      span.title-with-decoration.mb-5.col-sm-12 Funcion de los minerales

      
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/Tema1Img11.png')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Los minerales son nutrientes inorgánicos muy importantes para los sistemas del cuerpo humano, hacen parte de los órganos y elementos internos de este. Se adquieren a través de la ingesta de una gran serie de alimentos como las frutas y verduras. Los minerales contribuyen en la salud de los seres humanos, manteniendo el funcionando correctamente a las células de todos los órganos de del cuerpo, son responsables de activar la producción de líquidos y otras sustancias como las hormonas y las enzimas, también intervienen en procesos vitales de los seres vivos como la respiración, la digestión y la circulación de la sangre.
      
      p.mb-5 Los siguientes minerales hacen parte de los más importantes que necesitan los seres humanos para sobrevivir y se encuentran en diversas frutas y verduras.

      div.titulo-sexto.color-acento-botones.mb-5
        h5 Tabla 3.
        span Clasificación de verduras

      .tabla-a.color-acento-botones.mb-5.col-lg-10.mx-auto
        table
          caption Nota. Sena (2024)
          thead
            tr
              th Mineral
              th Funcion
              th Procedencia
          tbody
            tr
              td Hierro
              td Se encarga de producir hemoglobina en la sangre y participa en el transporte del oxígeno a través de todo el torrente sanguíneo.
              td Puede encontrarse en verduras de hojas verdes y en higos.
            tr
              td Magnesio
              td Ayuda al correcto funcionamiento de los músculos, conserva sanos a los huesos y a los dientes; además es de gran ayuda para las articulaciones de brazos y piernas.
              td El trigo, los fríjoles, el maíz, la avena, las almendras, las nueces, los higos y las verduras de hojas verdes.
            tr
              td Calcio
              td Es un mineral esencial para la formación de los huesos y los dientes, participa en las acciones que le permiten a la sangre coagularse, ayuda en las funciones musculares.
              td Puede encontrarse en verduras de hojas verdes y en semillas de ajonjolí y perejil.
            tr
              td Fósforo
              td Hace parte del proceso mediante el cual se forman los huesos y los dientes, también participa en la creación de las células.
              td Puede obtenerse de los cereales naturales, los fríjoles y las lentejas.
            tr
              td Selenio
              td Tiene propiedades antioxidantes y ayuda a prevenir el cáncer, además de facilitar el funcionamiento del corazón, el hígado y los órganos reproductivos.
              td Puede encontrarse en los cereales integrales y en gran parte de las verduras.
            tr
              td Potasio
              td Sirve para el funcionamiento adecuado de los riñones y del corazón. Participa en la transmisión de señales nerviosas y controla los niveles de agua en el cuerpo.
              td Todas las frutas, vegetales de hojas verdes y papas.
            tr
              td Sodio
              td Se ocupa del funcionamiento de los músculos y los nervios, regula los líquidos del cuerpo, contribuye a la correcta digestión de los alimentos y previene la deshidratación.
              td Puede encontrarse en los cereales.
            tr
              td Flúor
              td Hace parte de la composición de los huesos y dientes, además previene la aparición de caries dentales.
              td Se obtiene de frutas y verduras en general.
            tr
              td Zinc
              td Es importante para tener un adecuado desarrollo del cuerpo y sus tejidos como es el caso de la piel y el cabello.
              td Se le puede encontrar en legumbres, frutos secos y semillas de giraso


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
span.color-acento-darkgreen
  background-color: #33490B
  padding: 10px
  border-radius: 6px
  color: white
.container-orange
  background-color: #FB9231
.container-peach
  background-color: #FFE8D2
.boton.color-acento-darkgreen
  background-color: #33490B
.container-peach-2
  background-color: #FFF0D6
.acordion__activo
  background-color: #E6F1E8 !important
.acordion__accion__btn--a
  background-color: #F9A545
.acordion__activo .acordion__accion__btn--a
  background-color: #748578
thead
  background-color: #FFCE79
th
  background-color: #9EB682;

tr:nth-child(odd)
  background-color: #C7D5B6;

tr:nth-child(even)
  background-color: #E3EADA;
</style>
