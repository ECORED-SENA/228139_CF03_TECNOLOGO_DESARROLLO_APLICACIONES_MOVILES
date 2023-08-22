<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Validación de requerimientos

    .row
      .col-12.col-xl-8
        p(data-aos="fade") La validación de los requerimientos busca ratificar que los requerimientos realmente están especificando lo que el cliente desea y necesita. Este proceso es muy importante, pues un error en un documento de requerimientos puede ocasionar el desgaste importante de muchos recursos si estos errores son detectados en etapas más avanzadas del proyecto como diseño, construcción o despliegue a producción. Los costos asociados para el arreglo de problemas en los requerimientos siempre van a ser menores que en otras etapas, ya que un error en los requerimientos se propaga en cascada en todas las fases subsiguientes del ciclo de vida.
        p(data-aos="fade") Según Sommerville (2011), en el proceso de validación de requerimientos se llevan a cabo las siguientes verificaciones:
        ul.lista-ul.mt-4.mb-4(data-aos="fade")
          li
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Verificación de validez:] los requerimientos son razonables e identifican realmente todas las funciones necesarias para cumplir con las necesidades del cliente.
          li.mt-2
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Verificación de consistencia:] los requerimientos no presentan contradicciones.
          li.mt-2
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Verificaciones de completitud:]  se incluyen todas las funcionalidades y restricciones definidas por los usuarios del sistema.
          li.mt-2
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Verificaciones de realismo: ] los requerimientos son realizables de acuerdo con la tecnología existente, el presupuesto y los tiempos definidos.
          li.mt-2
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Verificabilidad: ] es posible demostrar la realización de cada requerimiento y que hace lo que debe hacer. Es decir, existe una forma clara en la que se le pueda realizar pruebas.


      .col-xl-4.d-none.d-xl-block
        figure.mb-5.px-4(data-aos="flip-up")
          img(src="@/assets/curso/temas/tema-1-1.svg", alt="")

    .tarjeta.tarjeta--azul.p-3.mb-5.mt-4
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1.mx-4
          img(src="@/assets/curso/temas/tema-1-2.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1 Infografía - Validación de requerimientos
              p.mb-0.text-small La validación de los requerimientos busca ratificar que los requerimientos realmente están especificando lo que el cliente desea y necesita.
            .col-sm-auto
              a.boton.color-acento-botones(href="/downloads/Infografia_Validacionderequerimientos.pdf" target="_blank")
                span Descargar
                i.fas.fa-file-download



    p Existen varias técnicas que pueden usarse para la validación de requisitos, como se puede revisar a continuación.

    Separador

    .titulo-segundo.mb-4(data-aos="fade-right")
      #t_1_1.h4 1.1. Revisiones de requerimientos

    p.mt-4(data-aos="fade") Las revisiones de los requerimientos es un proceso manual que involucra la participación de personas de parte de la organización constructora del software así como la de los clientes. Por lo general, en este proceso se revisa el documento de requerimientos tratando de encontrar alguna anomalía y/u omisiones en la escritura de estos.
    .row.mt-4.mx-0
      .cajon.cajon--azul.p-4.mb-5.mb-lg-0.bg-naranja-claro
        p.p-4 Esta revisión se puede realizar de manera informal o formal (Sommerville, 2011). En una revisión informal, se requiere verificar, con tantos stakeholders como sea posible, el documento generado para recibir confirmación por parte de ellos de que lo escrito sí refleja su deseo. Esta revisión informal permite, de manera muy sencilla, detectar muchos problemas antes de establecer cualquier formalismo de revisión.
    p.mt-4 En una revisión formal, el equipo de desarrollo debe introducir al cliente por cada uno de los requerimientos establecidos, y explicando cada una de sus implicaciones. El equipo encargado de la revisión deberá verificar cada requerimiento de forma individual y realizar el análisis de conjunto. Además, en el proceso de verificación debe resolverse cada una de las siguientes preguntas:
    .row.mt-4.mx-0
      .col-11.bg-verde-claro.mx-5.rounded
        .col-sm.mb-5.mb-sm-0.p-4.mt-3
          ul.lista-ul--color
            li.mt-2
              i.fas.fa-brain
              span #[strong Verificabilidad:] ¿Es posible probar este requerimiento en la realidad?
            li.mt-2
              i.fas.fa-brain
              span #[strong Comprensibilidad: ] ¿Es claro lo que expresa este requerimiento para las personas que lo van a usar?
            li.mt-2
              i.fas.fa-brain
              span #[strong Rastreabilidad:] ¿Es posible observar el origen del requerimiento y también evaluar los cambios que pueden generar en el sistema?
            li.mt-2
              i.fas.fa-brain
              span #[strong Adaptabilidad: ] ¿El cambio en el requerimiento impacta o no a gran escala sobre otros requerimientos?

    Separador

    .titulo-segundo.mb-4(data-aos="fade-right")
      #t_1_2.h4 1.2 Construcción de prototipos

    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/rVxFBN0q0tk" title="Construcción de prototipos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Construcción de prototipos

    p.mb-4 Por otra parte, el uso inadecuado de los prototipos también puede generar algunos riesgos, entre los que se encuentran:

    .row.mb-4.mx-0
      .col-11.bg-verde-claro.mx-5.rounded
        .col-sm.mb-5.mb-sm-0.p-4.mt-3
          ul.lista-ul--color
            li.mb-2
              i.fas.fa-brain
              span El prototipado puede estimular un número excesivo de cambios de peticiones.
            li.mb-2
              i.fas.fa-brain
              span Los prototipos operativos pueden inducir a pensar a la directiva y a los clientes que el producto final está prácticamente dispuesto para su salida al mercado.
            li.mb-2
              i.fas.fa-brain
              span Los prototipos pueden encarecer el producto.

    p Para la fase de verificación de requisitos se recomienda el uso de prototipos de baja fidelidad (presentación de escenarios con maquetas estáticas) y de tipo exploratorio (prototipos no reutilizables, usados únicamente para la clarificación e identificación de requerimientos).

    .row.mt-5.align-items-center.mb-5
      .col-4.d-none.d-md-block
        figure.px-4
          img(src="@/assets/curso/temas/tema-1-3.svg", alt="")
      .col-12.col-md-8
        p.mb-0 Aunque un prototipo podría ser una sencilla representación gráfica del sistema en papel o la representación de interfaces del sistema usando herramientas de ofimática, existen varias herramientas gratuitas y de pago que facilitan la construcción de prototipos, algunas de ellas solo requieren un registro de correo electrónico para acceder a sus funcionalidades directamente desde el navegador, y otras requieren la descarga e instalación en el equipo donde se planean construir los prototipos.

    p.mb-5 Algunas herramientas recomendadas son las siguientes:

    #herramientasUX
      .row.mb-4.align-items-stretch
        .col-sm-6.col-lg-3.mb-4.mb-lg-0

          .tarjeta--boton.p-5
            .row.justify-content-center.mb-3
              .col-8
                figure
                  img(src="@/assets/curso/temas/tema-1-4.svg", alt="Logo de la marca Adobe XD")

            h5.text-center Adobe XD
            p.text-small.text-center.ellipsis.mb-0
              a.mt-1(href="https://www.adobe.com/la/products/xd.html") www.adobe.com/la/products/xd.html

        .col-sm-6.col-lg-3.mb-4.mb-lg-0
          .tarjeta--boton.p-5
            .row.justify-content-center.mb-3
              .col-8
                figure
                  img(src="@/assets/curso/temas/tema-1-5.svg", alt="Logo de la marca Marvel App")

            h5.text-center Marvel App
            p.text-small.text-center.ellipsis.mb-0
              a.mt-1(href="www.marvelapp.com") www.marvelapp.com

        .col-sm-6.col-lg-3.mb-4.mb-lg-0

          .tarjeta--boton.p-5
            .row.justify-content-center.mb-3
              .col-8
                figure.my-4
                  img(src="@/assets/curso/temas/tema-1-6.svg", alt="Logo de la marca Moqups")

            h5.text-center Moqups
            p.text-small.text-center.ellipsis.mb-0
              a.mt-1(href="https://www.moqups.com") www.moqups.com

        .col-sm-6.col-lg-3.mb-4.mb-lg-0

          .tarjeta--boton.p-5
            .row.justify-content-center.mb-3
              .col-10
                figure.my-5
                  img(src="@/assets/curso/temas/tema-1-7.svg", alt="Logo de la marca LucidChart")

            h5.text-center LucidChart
            p.text-small.text-center.ellipsis.mb-0
              a.mt-1(href="https://www.lucidchart.com/pages/es") www.lucidchart.com/pages/es

    .row.align-items-stretch
      .col-sm-6.col-lg-3.mb-4.mb-lg-0

        .tarjeta--boton.p-5
          .row.justify-content-center.mb-3
            .col-8
              figure.my-4
                img(src="@/assets/curso/temas/tema-1-8.svg", alt="Logo de la marca Proto.io")

          h5.text-center Proto.io
          p.text-small.text-center.ellipsis.mb-0
            a.mt-1(href="https://www.proto.io") www.proto.io

      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.p-5
          .row.justify-content-center.mb-3
            .col-8
              figure.my-4
                img(src="@/assets/curso/temas/tema-1-9.svg", alt="Logo de la marca Balsamiq")

          h5.text-center Balsamiq
          p.text-small.text-center.ellipsis.mb-0
            a.mt-1(href="https://www.balsamiq.com") www.balsamiq.com

      .col-sm-6.col-lg-3.mb-4.mb-lg-0

        .tarjeta--boton.p-5
          .row.justify-content-center.mb-3
            .col-8
              figure.my-3
                img(src="@/assets/curso/temas/tema-1-10.svg", alt="Logo de la marca Wirify")

          h5.text-center Wirify
          p.text-small.text-center.ellipsis.mb-0
            a.mt-1(href="https://www.wirify.com") www.wirify.com

      .col-sm-6.col-lg-3.mb-4.mb-lg-0

        .tarjeta--boton.p-5
          .row.justify-content-center.mb-3
            .col-10
              figure.my-3
                img(src="@/assets/curso/temas/tema-1-11.svg", alt="Logo de la marca Picodo")

          h5.text-center Picodo
          p.text-small.text-center.ellipsis.mb-0
            a.mt-1(href="https://www.pidoco.com/en") www.pidoco.com/en

    Separador

    .titulo-segundo(data-aos="fade-right")
      #t_1_3.h4 1.3. Generación de casos de prueba

    p.mt-4(data-aos="fade") Desarrollar pruebas para los requerimientos permite evidenciar problemas antes de escribir cualquier línea de código. Normalmente si es complejo construir un caso de prueba para un requerimiento esto es un indicio de que el requerimiento puede ser difícil de implementar por lo que debería considerarse.
    .row.mt-5
      .col-4.d-none.d-md-block
        figure.mb-5.px-4
          img(src="@/assets/curso/temas/tema-1-12.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8
        p La validación de requisitos por casos de prueba requiere el desarrollo de cuatros fases: i) planeación de la prueba. Aquí se define la estrategia a utilizar, el alcance de la prueba a realizar y los tiempos requeridos para el desarrollo de la prueba; ii) diseño de los casos de prueba; iii) ejecución de los casos de prueba y iv) elaboración del informe final de la prueba donde se describen los aspectos más importantes y hallazgos de la ejecución de la prueba (Pantaleo, 2018).
    p.mb-5 De otra parte, el diseño de un caso de prueba requiere: i) la construcción de un instrumento donde se debe detallar para cada requerimiento si existen precondiciones, es decir, si se requieren de actividades o valores previos para poder iniciar la ejecución del requerimiento; ii) identificar los pasos a seguir para la validación de un requisito y iii) los resultados esperados de la realización de cada paso.
    .row.mt-4
      .col-10.offset-1
        //.titulo-sexto.color-acento-contenido
          h5 Figura 1
          span Formato de caso de prueba

        table
          caption Tabla 1 -  Formato de caso de prueba | Nota: Adaptado de Pantaleo (2018).
          thead.bg-amarillo
            tr.text-center
              th(colspan="2") Formato de caso de prueba
          tbody.bg-gris-claro
            tr
              th Objetivo del caso de prueba
              th
            tr
              th Identificador
              th
            tr
              th Nombre o identificador del requerimiento
              th
            tr
              th Precondiciones
              th
            tr
              th Pasos
              th Resultados esperados
            tr
              th 1.
              th 1.
            tr
              th 2.
              th 2.
            tr
              th 3.
              th 3.


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

<style lang="sass">
.bg-naranja-claro
  background-color: #FFE7C4
.text-align-right
  text-align: right
.borde-blanco
  border: 10px solid $white
.cajon--azul:before, .cajon:before
  background-color: $color-acento-botones
</style>
