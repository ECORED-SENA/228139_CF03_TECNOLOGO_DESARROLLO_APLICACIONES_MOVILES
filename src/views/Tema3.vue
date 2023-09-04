<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Herramientas para la gestión de requisitos

    .cajon.color-primario.p-4.mb-5
      .row.align-items-center
        .col-12.col-xl-9
          p.mb-4 En la actualidad, existe una variedad de herramientas para ser utilizadas específicamente en la gestión de requisitos, la utilización de estas ayuda a mejorar la calidad del desarrollo de un proyecto y permite un mayor control en el mantenimiento previniendo posibles errores durante la ejecución del proyecto (Sevilla, 2021).
          p Las herramientas de gestión de requisitos variarán según las metodologías de proyecto y los objetivos, la manera en la cual se aborden los requisitos también dependerá según la metodología. Por ejemplo, algunos equipos usan otra palabra para requisitos como “historias de usuarios”, “requisitos de productos” o, simplemente, “características”.

        .col-xl-3.d-none.d-lg-block
          figure.px-4
            img(src="@/assets/curso/temas/tema-3-1.svg", alt="")

    p.mb-5 Existen herramientas básicas de requerimientos y herramientas complejas, a reglón seguido se explican:

    .row.justify-content-center.mb-5
      .col-xl-4.mb-4.mb-lg-0
        .tarjeta--boton.p-4
          .row.justify-content-center.mb-3
            .col-8
              figure
                img(src='@/assets/curso/temas/tema-3-2.svg', alt='', style="max-width: 120px").m-auto

          h4.text-center Herramientas básicas
          p.lh-md.text-center Se manejan en la planeación de gestión de requisitos muy básica y se pueden utilizar las hojas de cálculo, o una plantilla de documento en Word; es difícil su utilización cuando se trata de actualización con varias personas y el manejo de las versiones de los documentos.

      .col-xl-4.mb-4.mb-lg-0
        .tarjeta--boton.p-4
          .row.justify-content-center.mb-3
            .col-8
              figure
                img(src='@/assets/curso/temas/tema-3-3.svg', style="max-width: 120px").m-auto

          h4.text-center Herramientas complejas
          p.lh-md.text-center Para una planificación de gestión de requisitos más compleja, se necesita un sistema de software completo para administrar las relaciones entre los requisitos, analizar el impacto de cualquier cambio, administrar las aprobaciones y demás aspectos.


    p.mb-5 De acuerdo con el mismo autor, las herramientas de gestión de requisitos se caracterizan por las siguientes propiedades:

    .row.justify-content-center.mb-5
      .col-xl-10
        .bg-gris.rounded.px-5.py-4
          ul.lista-ul.text-left
            li
              i.lista-ul__vineta(style="color: #ffa726;")
              span Gestión de requisitos basados en modelos de información como por ejemplo casos de uso o historias de usuario.
            li
              i.lista-ul__vineta(style="color: #ffa726;")
              span Organización de requisitos: es fácil agrupar el conjunto de requisitos y determinar su orden.
            li
              i.lista-ul__vineta(style="color: #ffa726;")
              span Acceso y gestión multiusuario: múltiples personas pueden participar en los procesos de construcción o modificación de requisitos.
            li
              i.lista-ul__vineta(style="color: #ffa726;")
              span Gestión de la trazabilidad: se puede ver a nivel histórico los cambios realizados en los requisitos con su marca de tiempo y usuarios involucrados.

    p.mb-4 Las siguientes herramientas principalmente ayudan a documentar, analizar, buscar, priorizar y trazar los requisitos:
    .row
      .col-10.offset-1

        table
          caption Tabla 1  - Herramientas de gestión de requisitos |  Nota: Tomada de Sevilla (2021).
          thead.bg-amarillo
            tr.text-center
              th Herramienta de gestión de requisitos
              th Compañía
              th URL
          tbody
            tr.bg-gris-claro
              th IBM Rational DOORS
              td IBM Rational
              th.ellipsis
                a.mt-1(href="https://www.ibm.com/es-es/products/requirements-management" target="_blank") ibm.com/es-es/products/requirements-management
            tr
              th Visure Requirements
              td Visure Solutions
              th.ellipsis
                a.mt-1(href="https://visuresolutions.com/visure-requirements-system-requirements/"  target="_blank") https://visuresolutions.com/visure-requirements-system-requirements/
            tr.bg-gris-claro
              th Reqtify
              td Dassault Systèmes
              th
                a.mt-1(href="https://www.claytex.com/products/reqtify/"  target="_blank") claytex.com/products/reqtify
            tr
              th Jama
              td Jama Software
              th.ellipsis
                a.mt-1(href="http://www.jamasoftware.com/"  target="_blank") jamasoftware.com
            tr.bg-gris-claro
              th Accept 360
              td Accept Software
              th.ellipsis
                a.mt-1(href="https://www3.technologyevaluation.com/solutions/17078/accept360"  target="_blank") technologyevaluation.com/solutions/17078/accept360
            tr
              th Gatherspace
              td Gatherspace
              th.ellipsis
                a.mt-1(href="https://www.gatherspace.com/project-management-software-solutions/"  target="_blank") gatherspace.com/project-management-software-solutions/
            tr.bg-gris-claro
              th RequisitePro
              td IBM Rational
              th.ellipsis
                a.mt-1(href="https://www.ibm.com/support/pages/rational-requisitepro-713"  target="_blank") ibm.com/support/pages/rational-requisitepro-713

    .row.mt-5
      p La norma ISO 24766 (Information Technology – Guide for Requirements Tool Capabilites) ayuda a seleccionar una herramienta adecuada de gestión de requisitos, pues la misma proporciona una orientación sobre los aportes de estas herramientas.
      p.mt-4 Aparte de las herramientas nombradas anteriormente, existen otras entre las que se encuentran las libres y comerciales; a continuación, se indican las más conocidas.

    TabsB.mt-5
      .py-4.py-md-5(titulo="Herramientas comerciales" :icono="require('@/assets/curso/temas/tema-3-10.svg')")
        .row.mt-4
          p Actualmente, se usan distintas herramientas de uso comercial que cubren las necesidades elementales en la gestión de requisitos. Algunas de estas son:
        .tabla-a.mb-5
          table
            tbody
              tr.bg-gris-claro
                td
                  .row
                    .col-12.text-center
                      figure.justify-content-center
                        img(src="@/assets/curso/temas/tema-3-4.svg", alt="Texto que describa la imagen").w-25.m-auto
                td
                  .row
                    .col-10.offset-1.justify-content-center
                      figure
                        img(src="@/assets/curso/temas/tema-3-5.svg", alt="Texto que describa la imagen").w-50.m-auto
                td
                  .row
                    .col-12.text-center
                      figure.justify-content-center
                        img(src="@/assets/curso/temas/tema-3-6.svg", alt="Texto que describa la imagen").w-50.m-auto
              tr.bg-gris-claro
                td.text-center.px-4 Aplicación de gestión de requisitos para optimizar la comunicación, la colaboración y la verificación de requisitos.
                td.text-center.px-4 Herramienta de administración de requisitos que permite crear y compartir basado en documentos potenciados.
                td.text-center.px-4.py-5 Herramienta de administración de requisitos que permite visibilidad y control.
      .py-4.py-md-5(titulo="Herramientas libres" :icono="require('@/assets/curso/temas/tema-3-11.svg')")
        .row.mt-4
          p También existen herramientas de uso libre para realizar las actividades pertinentes a la gestión de requisitos. Algunas son:
        .tabla-a.mb-5
          table
            tbody
              tr.bg-gris-claro
                td
                  .row
                    .col-12.text-center
                      figure.justify-content-center
                        img(src="@/assets/curso/temas/tema-3-7.svg", alt="Texto que describa la imagen").w-50.m-auto
                td
                  .row
                    .col-10.offset-1.justify-content-center
                      figure
                        img(src="@/assets/curso/temas/tema-3-8.svg", alt="Texto que describa la imagen").w-50.m-auto
                td
                  .row
                    .col-12.text-center
                      figure.justify-content-center
                        img(src="@/assets/curso/temas/tema-3-9.svg", alt="Texto que describa la imagen").w-25.m-auto
              tr.bg-gris-claro
                td.text-center.px-4 Herramienta de requisitos automatizada.
                td.text-center.px-4 Totalmente desarrollada para la elicitación de requisitos.
                td.text-center.px-4.py-5 Permite la descripción avanzada de diversos tipos de requisitos y garantiza la trazabilidad entre todos los documentos relacionados con la ingeniería de requisitos (funcionalidades, requisitos, casos de uso, casos de prueba).
</template>

<script>
export default {
  name: 'Tema3',
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
.bg-gris
  background-color: #E3EDF8
</style>
