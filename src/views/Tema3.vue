<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Tipología calzado Oxford y sus variaciones
    
    .bg-color-16.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/temas/tema3/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") El calzado Oxford es un tipo de zapato clásico, cerrado y elegante, reconocido por su diseño sobrio y la costura característica que une la parte frontal con los laterales (conocida como "cerradura inglesa"). Se distingue principalmente por su sistema de cordones cerrados, que le otorga una apariencia más formal en comparación con otros estilos de calzado.
    
    Separador

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        #t_3_1.titulo-segundo.color-acento-contenido
          h2 3.1 Reseña histórica
        
        .row.mb-5
          .col-lg-5.order-2
            figure
              img(src="@/assets/curso/temas/tema3/2.png", data-aos="zoom-in")
          .col-lg-7.order-1.mb-3.mb-lg-0
            p.mb-5(data-aos="fade-left") El calzado Oxford tiene sus orígenes en las Islas Británicas, particularmente en Escocia e Irlanda, donde existía un modelo similar conocido como "Balmoral". Sin embargo, fue en Inglaterra donde adquirió notoriedad y su nombre actual, gracias a los estudiantes de la Universidad de Oxford. A mediados del siglo XIX, estos jóvenes comenzaron a usar este estilo como una alternativa más cómoda y moderna a las tradicionales botas altas, marcando así el inicio de su popularidad.
        
            .bg-color-7.p-4(data-aos="fade-left")
              p.mb-0 Inicialmente considerado un zapato informal, el Oxford fue evolucionando hasta convertirse en un símbolo de elegancia y distinción, especialmente en el vestir masculino. Su característica principal —el sistema de cordones cerrados— le confiere una apariencia ajustada, sobria y refinada, diferenciándolo de otros estilos de calzado.
        .row.mb-5
          .col-lg-4.mb-3.mb-lg-0
              img(src="@/assets/curso/temas/tema3/3.png", data-aos="zoom-in")
          .col-lg-8
            p.mb-5(data-aos="fade-left") Con el paso de los años, este modelo se ha adaptado a nuevas tendencias y contextos. Aunque su estructura básica se ha mantenido, han surgido diversas variaciones que han permitido su uso en escenarios formales, semiformal e incluso casual. Asimismo, su diseño ha sido adoptado en la moda femenina, ampliando su alcance y versatilidad.
        
            .bg-color-16.p-4(data-aos="fade-left")
              p.mb-0 Actualmente, el Oxford es considerado un clásico atemporal dentro del diseño de calzado. Su equilibrio entre tradición, sofisticación y adaptabilidad lo convierte en una pieza clave en la confección de calzado de vestir, manteniéndose vigente en la moda contemporánea.

    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Variaciones del Modelo Oxford
    
    p.mb-4 El modelo Oxford, reconocido por su elegancia y diseño clásico con cordones cerrados, ha evolucionado a lo largo del tiempo, dando origen a diferentes versiones que permiten su uso en contextos formales, semiformal e incluso casual. A continuación, se describen las principales variaciones del calzado Oxford:

    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-down")
      .p-4.p-md-5       
        .tarjeta.bg-color-white.p-4.p-lg-5.pb-lg-4.shadow-soft(data-aos="fade-up")
          SlyderA(tipo='b')
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Oxford liso
                p Es la versión más sencilla y formal del calzado Oxford. No presenta decoraciones ni costuras adicionales, lo que le confiere una apariencia limpia y elegante, ideal para eventos de etiqueta.
              .col-lg-5
                img(src='@/assets/curso/temas/tema3/4.png', alt="").mx-auto
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Oxford con puntera
                p Incorpora una costura horizontal o un corte que separa la puntera del resto del zapato. Es una de las variaciones más comunes, combinando elegancia con un toque de distinción, ideal para el ámbito ejecutivo o semiformal.  
              .col-lg-5
                img(src='@/assets/curso/temas/tema3/5.png', alt="").mx-auto
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Oxford con bigotera
                p Se distingue por una puntera decorativa en forma de "W" o alas, acompañada de perforaciones ornamentales (<em>broguing</em>). Es una versión menos formal y más estilizada, adecuada para contextos semiformal o casual.
              .col-lg-5
                img(src='@/assets/curso/temas/tema3/6.png', alt="").mx-auto
           
        


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

<style lang="sass"></style>
