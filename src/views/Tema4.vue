<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Moldes, conceptos y tipos
    
    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema4/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los moldes o patrones son plantillas planas que representan las distintas piezas que conforman la capellada del calzado. A partir de ellos se realiza el corte y el ensamblaje de los materiales que darán forma al producto final. Son fundamentales para asegurar precisión, simetría, confort y diseño en cada referencia de calzado.
          br
          | El desarrollo de los moldes parte del perfil de la horma, obtenido mediante técnicas como el enmascarado, el trazado de líneas guía y la creación de una máscara compensada. Con base en esta plantilla, se diseñan y trazan las piezas que luego se escalarán de acuerdo con las tallas requeridas.
    
    p.mb-4 Entre los principales tipos de moldes utilizados en la fabricación de calzado se encuentran:

    .bg-full-width-2.bg-fondo-7
      .p-4.p-md-5
        .carousel-bg
          .row.justify-content-center.align-items-center.my-5
            .col-lg-3.d-none.d-lg-block(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/tema4/2.png', alt='', style="max-width: 300px").mx-auto
            .col-lg-8
              SlyderF.mb-5(columnas="col-lg-6")(data-aos="zoom-in-up")
                .tarjeta.bg-color-white.p-4.shadow-top-left-right.text-center
                  img(src='@/assets/curso/temas/tema4/3.svg', style="max-width: 89px", alt='').mx-auto.mb-4
                  .bg-color-8.d-inline-block.px-2.py-1.mb-3
                    h4.text-center.mb-0.text-color-black #[strong Moldes base o patrón]
                  p.text-center Definen la estructura del modelo y sirven como referencia para generar variantes.

                .tarjeta.bg-color-white.p-4.shadow-top-left-right.text-center
                  img(src='@/assets/curso/temas/tema4/4.svg', alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  .bg-color-8.d-inline-block.px-2.py-1.mb-3
                    h4.text-center.mb-0.text-color-black #[strong Moldes de corte]
                  p.text-center Se utilizan para cortar los materiales definitivos que conforman la capellada.

                .tarjeta.bg-color-white.p-4.shadow-top-left-right.text-center
                  img(src='@/assets/curso/temas/tema4/5.svg', alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  .bg-color-8.d-inline-block.px-2.py-1.mb-3
                    h4.text-center.mb-0.text-color-black #[strong Moldes de forro y refuerzo]
                  p.text-center Corresponden a las piezas internas que aportan estructura, confort y durabilidad

                .tarjeta.bg-color-white.p-4.shadow-top-left-right.text-center
                  img(src='@/assets/curso/temas/tema4/6.svg', alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  .bg-color-8.d-inline-block.px-2.py-1.mb-3
                    h4.text-center.mb-0.text-color-black #[strong Moldes de montaje o plantillas de armado]
                  p.text-center Guían el proceso de ensamblaje del calzado.
                .tarjeta.bg-color-white.p-4.shadow-top-left-right.text-center
                  img(src='@/assets/curso/temas/tema4/7.svg', alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  .bg-color-8.d-inline-block.px-2.py-1.mb-3
                    h4.text-center.mb-0.text-color-black #[strong Moldes de rayado o marcación]
                  p.text-center Permiten señalar sobre el material las líneas de doblez, costuras, piquetes, centros y otras marcas técnicas necesarias para un ensamblaje preciso.
   
        .row.align-items-center.px-4.px-md-5.py-4.bg-color-8.tarjeta
          .col-lg-auto
            img(src="@/assets/curso/temas/tema4/8.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0
              strong ¿Por qué es importante este tema?
              | La creatividad es una herramienta fundamental en cualquier ámbito profesional. Ya sea que se dediquen al marketing, al diseño, a la programación o a cualquier otra área, la capacidad de generar ideas nuevas y originales, le permitirá destacar y alcanzar el éxito.


</template>

<script>
export default {
  name: 'Tema4',
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
