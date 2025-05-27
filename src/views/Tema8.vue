<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Elaboración maqueta de comprobación
    
    .bg-color-16(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/temas/tema8/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") La maqueta es una representación tridimensional del diseño del calzado, elaborada a partir de los moldes iniciales. Se emplea como herramienta de verificación durante el desarrollo del patrón, permitiendo al patronista analizar de manera práctica cómo se ajustan y se comportan las piezas del diseño sobre la horma.
    separador

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        #t_8_1.titulo-segundo.color-acento-contenido
          h2 8.1 Funciones principales de la maqueta

        p.mb-4 La maqueta cumple varias funciones esenciales dentro del proceso de patronaje:

        .row.align-items-start
          .col-lg-3.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/temas/tema8/2.png", alt="").mb-4.mb-lg-0
          .col-lg-9
            AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonB")
              .div(titulo="Verificar el ajuste")
                p Permite comprobar si las piezas del molde encajan correctamente sobre la horma, identificando tensiones, pliegues o sobrantes.
              .div(titulo="Evaluar el diseño")
                p Ayuda a revisar la distribución estética de las piezas (capellada, cordonera, talón, puntera, entre otras) y confirmar que respeten las proporciones y líneas proyectadas.
              .div(titulo="Corregir inconsistencias")
                p Facilita la detección de errores o desajustes en el trazado del molde, permitiendo hacer correcciones antes de cortar en materiales definitivos.
              .div(titulo="Optimizar tiempos y materiales")
                p Al identificar errores tempranamente, se reduce el desperdicio de material y se evitan retrabajos durante la producción.
    separador

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        #t_8_2.titulo-segundo.color-acento-contenido
          h2 8.2 Materiales comunes para la elaboración de maquetas

        p.mb-4 Los materiales más utilizados para construir maquetas de comprobación son:

        .bg-full-width.bg-fondo-slider(data-aos="fade-down")
          .p-4.p-md-5       
            .tarjeta.bg-color-white.p-4.p-lg-5.pb-lg-4.shadow-soft(data-aos="fade-up")
              SlyderA(tipo='b')
                .row.pt-lg-4.align-items-center
                  .col-lg-7.mb-4.mb-lg-0
                    h5 Papel <em>kraft</em> o cartulina
                    p Fáciles de manipular y económicos, ideales para pruebas preliminares.
                  .col-lg-5
                    img(src='@/assets/curso/temas/tema8/3.png', alt="").mx-auto
                .row.pt-lg-4.align-items-center
                  .col-lg-7.mb-4.mb-lg-0
                    h5 <em>Telford</em>
                    p Plástico delgado y flexible que ofrece mayor precisión en el ajuste y permite una revisión detallada del diseño.
                  .col-lg-5
                    img(src='@/assets/curso/temas/tema8/4.png', alt="").mx-auto
                .row.pt-lg-4.align-items-center
                  .col-lg-7.mb-4.mb-lg-0
                    h5 <em>Cambrelle</em>
                    p Tejido no tejido que simula mejor el comportamiento de materiales reales como la lona o el forro.
                  .col-lg-5
                    img(src='@/assets/curso/temas/tema8/5.png', alt="").mx-auto
                .row.pt-lg-4.align-items-center
                  .col-lg-7.mb-4.mb-lg-0
                    h5 Cuero (retales)
                    p Utilizado en maquetas más avanzadas cuando se requiere una verificación más cercana al calce y acabado reales.
                  .col-lg-5
                    img(src='@/assets/curso/temas/tema8/6.png', alt="").mx-auto

    separador

   
    #t_8_3.titulo-segundo.color-acento-contenido
      h2 8.3. Importancia de la maqueta

    .row.align-items-center.px-4.px-md-5.py-4.bg-color-16.tarjeta
      .col-lg-auto
        img(src="@/assets/curso/temas/tema8/7.svg", style="max-width: 90px").mx-auto
      .col-lg
        p.mb-0 El uso de maquetas es una práctica clave en el diseño de calzado, ya que permite detectar oportunamente fallas estructurales o estéticas. Gracias a este paso, se garantiza que el producto final no solo cumpla con las condiciones de funcionalidad y comodidad, sino que también conserve una composición visual equilibrada.




</template>

<script>
export default {
  name: 'Tema8',
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
