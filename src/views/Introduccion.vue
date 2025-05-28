<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .bg-full-width-2.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        p La fabricación de calzado de calidad requiere precisión en cada etapa del proceso, especialmente en el desarrollo de moldes, que sirven como base estructural para la creación de cada modelo. En el caso del calzado tipo Oxford, caracterizado por su diseño clásico y elegante, el dominio de técnicas de patronaje resulta fundamental para garantizar un ajuste adecuado, una apariencia estética y una producción estandarizada. Este componente formativo ofrece a los participantes las habilidades necesarias para elaborar moldes que respeten las especificaciones técnicas y estilísticas del diseño Oxford.
        .row.mb-5.justify-content-center
          .col-xl-9
            .bg-color-19.mb-3(data-aos="fade-up")
              .row.justify-content-center.align-items-center
                .col-xl-auto
                  figure
                    img(src='@/assets/curso/intro/1.png', alt='')
                .col-xl
                  .p-4
                    p.mb-0(data-aos="fade-up") A lo largo del eje, se abordarán los procedimientos esenciales para la construcción de moldes, comenzando con el enmascarado de la horma, la obtención de la camisa o trepa, y la creación del molde patrón. También se profundizará en el despiece de moldes para diferentes variaciones del modelo Oxford, como el Oxford liso, con puntera, con talón y con bigotera, asegurando que cada participante adquiera un conocimiento completo sobre las adaptaciones técnicas y estéticas requeridas en cada variante.
            
            
            p(data-aos="fade-left") Finalmente, se incluirá la elaboración de maquetas de comprobación, una herramienta fundamental para validar la precisión del patronaje antes de pasar a la fabricación definitiva. A través de este proceso, los aprendices no solo consolidarán su dominio técnico, sino que también desarrollarán un criterio crítico que les permitirá evaluar y optimizar sus moldes, garantizando productos de alta calidad en la industria del calzado.
          .col-md-8.col-xl-3.d-none.d-sm-block
            figure
              img(src="@/assets/curso/intro/2.png", data-aos="zoom-in").mb-4.mb-lg-0
    

</template>

<script>
export default {
  name: 'Introduccion',
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
