<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Requerimientos duraderos y volátiles

    figure.mb-5(data-aos="flip-up")
      img(src="@/assets/curso/temas/tema-2-1.svg", alt="")

    p(data-aos="fade") Los requerimientos de un proyecto inevitablemente sufren variaciones en el tiempo y puede ser por varios motivos entre los que se podrían destacar cambios en las políticas gubernamentales, sociales, económicas o, sencillamente, por solicitudes de los clientes.
    p(data-aos="fade") Según Sommerville (2011), dependiendo de la perspectiva evolutiva de los requerimientos, estos se pueden clasificar en dos grupos:

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul").mt-4
      .row(titulo="Requerimientos duraderos:")
        p Son relativamente estables y normalmente se derivan de las actividades principales de la organización y están directamente relacionados con el dominio del sistema (Easterbrook, 1993). Por ejemplo, en un sistema académico los requerimientos relacionados con la gestión de estudiantes, profesores y grupos hacen parte del dominio y, seguramente, el modelo de negocio asociado a estos requerimientos no van a cambiar mucho en el tiempo.

      .row(titulo="Requerimientos volátiles:")
        p Son los que, muy probablemente, cambian durante el proceso del desarrollo del sistema o después que este entra en funcionamiento. Por ejemplo, en un sistema académico un requerimiento asociado al proceso de pago de pensión podría definirse de forma manual en un principio; es decir, la secretaria una vez reciba el dinero o los recibos de pago registra el pago en el sistema, más adelante si la institución educativa adquiere un servicio de pasarela de pagos en línea el requerimiento podría modificarse totalmente.
        p Los requerimientos volátiles según Sommerville (2011) se clasifican en:
        ul.lista-ul.mb-4
          li
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Requerimientos cambiantes:] cambian de acuerdo con el entorno, por ejemplo: una pandemia.
          li
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Requerimientos emergentes:] surgen como producto de un mejor entendimiento del sistema, por ejemplo, al estructurar el diseño de las interfaces del sistema puede ser que se requieran adicionar componentes que no estaban contemplados.
          li
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Requerimientos consecuentes:] son resultado de la puesta en marcha de un sistema. Generalmente la adopción de un nuevo sistema involucra el cambio de procesos e incluso roles dentro de la organización que, a la vez, puede influir en cambios en los requerimientos del sistema.
          li
            i.lista-ul__vineta(style="color: #ffa726;")
            span #[strong Requerimientos de compatibilidad:] dependen de otros sistemas o procesos, cuando estos cambian generalmente producen también cambios en los requerimientos dependientes.

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

<style lang="sass">
.tarjeta--amarilla
  background-color: black
</style>
