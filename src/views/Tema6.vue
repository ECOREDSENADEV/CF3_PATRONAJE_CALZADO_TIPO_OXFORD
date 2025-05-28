<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Elaborar moldes para el modelo tipo Oxford con puntera y talón
    
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema6/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El modelo Oxford con puntera y talonera es una variante del Oxford liso. Sigue la misma metodología y emplea los mismos puntos y líneas guía del modelo original. Por esta razón, se puede utilizar el mismo molde patrón, realizando el respectivo giro y ubicando el nuevo punto de atraque.

    separador

    #t_6_1.titulo-segundo.color-acento-contenido
      h2 6.1 Elaborar molde patrón para el modelo tipo Oxford con puntera y talón
    
    p.mb-5 Para elaborar el molde patrón de este modelo se deben realizar los siguientes trazos:

    .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
      h4(data-aos="fade-up") Dibujo de capellada, cordonera y lengüeta
    
    .row.mb-5.align-items-center
      .col-lg-3.order-2
        figure
          img(src="@/assets/curso/temas/tema6/2.svg", data-aos="zoom-in")
      .col-lg-9.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") La construcción de la capellada, cordonera y lengüeta se realiza de la misma forma que en el modelo Oxford liso, incluyendo el aumento de montaje de 17 mm.
    
    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 36.
          span Construcción capellada, cordonera y lengüeta
        figure
          img(src="@/assets/curso/temas/tema6/3.png", data-aos="zoom-in", alt="Construcción simultánea de capellada, cordonera y lengüeta en el molde patrón para el modelo Oxford con puntera y talón, respetando los aumentos de montaje. ")
    
    .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
      h4(data-aos="fade-up") Construcción de la puntera
    
    p.mb-4 El trazo de la puntera se lleva a cabo de la siguiente manera:

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center
          .col-lg-10
            .bg-color-7.mb-5(data-aos="fade-up")
              .row.justify-content-center.align-items-center
                .col-lg-auto.mb-3.mb-lg-0
                  figure
                    img(src='@/assets/curso/temas/tema6/4.png', alt='')
                .col-lg
                  .p-4
                    ul.lista-ul--color.mb-0
                      li.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Mida la distancia desde la línea de plantilla hasta el punto de calzada sobre la línea de capellada.
                      li.mb-0.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Divida esta distancia en tres partes iguales.
                      li.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Desde la línea de plantilla, tome 2/3 de esta medida y marque un punto sobre la capellada, denominado punto máximo de puntera.
                      li.mb-0.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Desde este punto, marque otro a 10 mm en dirección a la punta, llamado punto inferior de puntera.
                      li.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Trace líneas perpendiculares (90°) desde ambos puntos hasta la línea de plantilla.
                      li.mb-0.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Dibuje la curva de la puntera uniendo el punto máximo y el punto inferior, extendiéndola hasta la línea de montaje, asegurándose de conservar un diseño estético.
        .row.mb-5.justify-content-center.align-items-center
          .col-lg-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 37.
              span Elaboración puntera
            figure
              img(src="@/assets/curso/temas/tema6/5.png", data-aos="zoom-in", alt="Elaboración de la puntera mediante divisiones proporcionales entre la línea de plantilla y el punto de calzada, formando los puntos máximos e inferiores de la pieza.  ")
        
        .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
          h4(data-aos="fade-up") Construcción del talón
    
    p.mb-4 La construcción del talón comprende los siguientes pasos:

    .bg-color-25.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0.order-2
          figure
            img(src='@/assets/curso/temas/tema6/6.png', alt='')
        .col-lg.order-1(data-aos="fade-up")
          .p-4
            ul.lista-ul--color.mb-0
              li.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Desde el punto de altura de talón, mida 20 mm sobre la línea de profundidad hacia adelante para definir la cabeza del talón.
              li.mb-0.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Trace una línea perpendicular desde este punto hacia la línea de plantilla, estableciendo el cuello del talón.
              li.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Dibuje una línea paralela a 15 mm por debajo de la línea de profundidad para definir el ancho de la talonera.
              li.mb-0.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Localice el cruce entre la línea de la boca de la cordonera y la línea de plantilla; desde ahí, mida 15 mm hacia atrás sobre la línea de plantilla para establecer el largo del talón.
              li.mb-0.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Trace una línea perpendicular a la línea de profundidad desde ese punto.
              li.mb-0.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Marque un punto a 20 mm desde la línea de plantilla sobre la línea del talón y dibuje el eje de la talonera uniendo este nuevo punto con el punto de ajuste del talón.
              li.mb-0.d-flex
                i.fas.fa-circle-check.bg-color-21
                p.mb-0 Ajuste las curvas para definir la forma final del talón.
    
    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 38.
          span Construcción talón
        figure
          img(src="@/assets/curso/temas/tema6/7.png", data-aos="zoom-in", alt="Trazado del talón para el Oxford con puntera y talón, estableciendo los ejes, anchos y longitudes específicas para una estructura simétrica y proporcionada. ")
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 39.
          span Talón
        figure
          img(src="@/assets/curso/temas/tema6/8.png", data-aos="zoom-in", alt="Vista del talón una vez definido el diseño final, incluyendo los ajustes de forma para su integración con las demás piezas del calzado. ")   

    separador

    #t_6_2.titulo-segundo.color-acento-contenido
      h2 6.2 Despiece de moldes para el modelo tipo Oxford con puntera y talón 

    p.mb-4 Antes de proceder con el despiece, es necesario realizar los aumentos de armado en las piezas del modelo.  

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
          .col-lg-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 40.
              span Aumentos de armado
            figure
              img(src="@/assets/curso/temas/tema6/9.png", data-aos="zoom-in", alt="Ilustración de las áreas donde se deben realizar los aumentos de armado sobre las piezas del molde patrón, antes del calado")
        p.mb-4 Una vez aplicados los aumentos, realice cortes en forma de canal sobre las líneas internas del molde patrón, es decir, el proceso de calado.

        .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
          .col-lg-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 41.
              span Calado molde patrón
            figure
              img(src="@/assets/curso/temas/tema6/10.png", data-aos="zoom-in", alt="Imagen que muestra el proceso de calado del molde patrón, realizando cortes en forma de canal sobre las líneas internas para separar piezas. ")
    
    .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
      h4(data-aos="fade-up") Molde de puntera
    
    .row.mb-5
      .col-lg-5.order-2
        .titulo-sexto.color-acento-contenido
          h5 Figura 42.
          span Eje de puntera
        figure
          img(src="@/assets/curso/temas/tema6/11.png", data-aos="zoom-in", alt="Trazado de los ejes de la puntera, ubicando los puntos de referencia para el corte y separación precisa de esta pieza del molde principal. ")
      .col-lg-7.order-1.mb-3.mb-lg-0
        .bg-color-16.p-5.h-100(data-aos="fade-left")
          p Para construir el molde de la puntera:
          ul.lista-ul--color
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Ubique un punto 4 mm por encima del punto de calzada sobre el eje del empeine.
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Marque otro punto 10 mm adelante del punto máximo de la puntera.
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Una ambos puntos con una línea recta, extendiéndola hasta la línea de montaje.
    
    p.mb-4 Doble una cartulina, coloque sobre ella el nuevo eje de la puntera, dibuje el contorno de la pieza y recórtela cuidadosamente. Si la puntera se pliega, añada un aumento de 5 mm en la parte superior.

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
          .col-lg-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 43.
              span Despiece puntera
            figure
              img(src="@/assets/curso/temas/tema6/12.png", data-aos="zoom-in", alt="Despiece final de la puntera, elaborado sobre cartulina, listo para su recorte y aplicación de aumentos si es necesario. ")
        
        .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
          h4(data-aos="fade-up") Molde de capellada
        .row.mb-5
          .col-lg-5.order-2
            .titulo-sexto.color-acento-contenido
              h5 Figura 44.
              span Despiece capellada
            figure
              img(src="@/assets/curso/temas/tema6/13.png", data-aos="zoom-in", alt="Despiece de la capellada doblando la cartulina sobre el eje, asegurando simetría perfecta para la pieza principal del Oxford. ")
          .col-lg-7.order-1.mb-3.mb-lg-0
            .bg-color-16.p-5.h-100(data-aos="fade-left")
              p El molde de la capellada se obtiene así:
              ul.lista-ul--color
                li.d-flex
                  i.fas.fa-circle-check.bg-color-21
                  p.mb-0 Doble una cartulina por la mitad.
                li.d-flex
                  i.fas.fa-circle-check.bg-color-21
                  p.mb-0 Ubique sobre el pliegue el molde patrón, asegurándose de que el eje de la capellada coincida con el doblez.
                li.d-flex
                  i.fas.fa-circle-check.bg-color-21
                  p.mb-0 Marque y recorte, incluyendo los aumentos necesarios para el armado.
    
        
    .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
      h4(data-aos="fade-up") Molde de cordonera
    .row.mb-5
      .col-lg-5.order-2
        .titulo-sexto.color-acento-contenido
          h5 Figura 45.
          span Despiece cordonera
        figure
          img(src="@/assets/curso/temas/tema6/14.png", data-aos="zoom-in", alt="Despiece de la cordonera, marcado directamente sobre cartulina, mostrando las líneas internas y los ajustes de aumento requeridos. ")
      .col-lg-7.order-1.mb-3.mb-lg-0
        .bg-color-23.p-5.h-100(data-aos="fade-left")
          p Para la cordonera:
          ul.lista-ul--color
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Coloque la copia sobre una cartulina.
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Marque las líneas de la cordonera con un portaminas.
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Recorte con una cuchilla.
            li.d-flex
              i.fas.fa-circle-check.bg-color-21
              p.mb-0 Si la pieza se pliega, aplique un aumento de 5 mm en la parte superior.
    
    .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
      h4(data-aos="fade-up") Molde de talón
    
    p.mb-4 El molde del talón se desarrolla de la siguiente manera:

    .bg-full-width-2.bg-color-22
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center
          .col-lg-10
            .bg-color-25.mb-5(data-aos="fade-up")
              .row.justify-content-center.align-items-center
                .col-lg-auto.mb-3.mb-lg-0
                  figure
                    img(src='@/assets/curso/temas/tema6/15.png', alt='')
                .col-lg
                  .p-4
                    ul.lista-ul--color.mb-0
                      li.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Trace una línea recta desde el punto de ajuste del talón, ubicado sobre la línea de profundidad, hasta el cruce de la línea del talón con la línea de plantilla.
                      li.mb-0.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Doble una cartulina y ubique sobre el pliegue el eje obtenido.
                      li.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Dibuje el contorno del talón y recorte, asegurando la simetría.
                      li.mb-0.d-flex
                        i.fas.fa-circle-check.bg-color-21
                        p.mb-0 Ajuste las líneas del diseño y aplique los aumentos necesarios: 5 mm en todo el contorno (excepto en la parte inferior) y 2 mm adicionales en la unión inferior del talón.

        .row.mb-5.justify-content-center.align-items-center
          .col-lg-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 46.
              span Despiece talón
            figure
              img(src="@/assets/curso/temas/tema6/16.png", data-aos="zoom-in", alt="Despiece del talón con trazado simétrico sobre cartulina plegada, contemplando aumentos en los contornos para facilitar el armado final.")    
    
    .row.justify-content-center
      .col-lg-10
        .bg-color-24.mb-5(data-aos="fade-left")
          .row.justify-content-center.align-items-center
            .col-lg-auto.mb-3.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema6/17.png', alt='')
            .col-lg
              .p-4
                h5 Moldes de forro para el modelo tipo Oxford con puntera y talón
                p.mb-0(data-aos="fade-up") Los moldes de forro para este modelo se elaboran siguiendo el mismo procedimiento descrito para el modelo Oxford liso, aplicando las mismas técnicas de giro y ajuste.


</template>
<script>
export default {
  name: 'Tema6',
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
