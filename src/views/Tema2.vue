<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Obtener camisa (trepa) de forma manual
    
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El desarrollo de moldes para calzado requiere precisión y dominio técnico en cada una de sus etapas. Uno de los pasos fundamentales es el trazado de puntos y líneas guía sobre la horma, ya que permiten definir la forma y las proporciones del modelo. A partir de este trazado, se realiza el enmascarado de la horma, se obtiene la camisa y, posteriormente, se genera la máscara compensada, que sirve como base para el diseño del molde patrón. Este proceso garantiza simetría, ajuste y funcionalidad en la fabricación del calzado.
    
    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-down")
      .p-4.p-md-5       
        .tarjeta.bg-color-white.p-4.p-lg-5.pb-lg-4.shadow-soft(data-aos="fade-up")
          SlyderA(tipo='b')
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Enmascarado de la horma para obtener la camisa
                p Durante el proceso de elaboración de la camisa, es fundamental realizar el enmascarado en ambas caras de la horma, tanto interna como externa, con el objetivo de obtener un perfil preciso que garantice la correcta construcción del molde.
              .col-lg-5
                img(src='@/assets/curso/temas/tema2/2.png', alt="Esquema comparativo de mascaras externa e interna para diseño de calzado, con líneas geométricas que definen segmentos sobre la silueta lateral de un zapato. ").mx-auto
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Superposición de máscaras externa e interna
                p Una vez se han obtenido ambas máscaras, estas se superponen procurando que coincidan la altura del talón y la línea de profundidad, lo que permite asegurar la simetría y precisión del molde.   
              .col-lg-5
                img(src='@/assets/curso/temas/tema2/3.png', alt="Esquema de superposición de máscaras externa e interna para molde de calzado, donde se alinean la altura del talón y la línea de profundidad ").mx-auto
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Promediado de curvas para obtener la máscara compensada
                p Se realiza un promedio entre las curvas obtenidas de ambas máscaras para generar una nueva curva más precisa y equilibrada, que servirá como base para el desarrollo de la camisa.
              .col-lg-5
                img(src='@/assets/curso/temas/tema2/4.png', alt="Esquema de promediado de curvas de máscaras externa e interna para calzado, con líneas negras, rojas y azules que representan las siluetas individuales y la curva resultante.  ").mx-auto
            .row.pt-lg-4.align-items-center
              .col-lg-7.mb-4.mb-lg-0
                h5 Esquema de máscara compensada para diseño de molde patrón de calzado
                p De esta manera se obtiene la máscara compensada, producto del ajuste y promediado de ambas curvas, la cual proporciona una base simétrica y precisa para el trazado del molde patrón. Para este procedimiento, se tomarán como referencia las líneas y puntos guías correspondientes a la cara externa de la horma.
              .col-lg-5
                img(src='@/assets/curso/temas/tema2/5.png', alt="Esquema de la máscara compensada para calzado que representa el contorno lateral de una horma con líneas guía rectas y puntos de referencia ").mx-auto
    
    .titulo-tres.mb-4(data-aos="flip-up").mb-4.mt-5
      h4(data-aos="fade-up") Recorte de las piezas simétricas de la camisa
    
    .row.mb-5
      .col-lg-3.order-2
        figure
          img(src="@/assets/curso/temas/tema2/6.svg", data-aos="zoom-in")
      .col-lg-9.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") A partir de la máscara compensada, se procede a recortar dos piezas simétricas que serán ensambladas para conformar la camisa de la horma. Estas piezas pueden elaborarse en diversos materiales, como papel, telfor o cambrelle; en este caso, se utilizará papel para facilitar el trazado y los ajustes necesarios.

    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 14.
          span Recorte de las piezas simétricas de la camisa
        figure
          img(src="@/assets/curso/temas/tema2/7.png", data-aos="zoom-in", alt="Recorte de dos piezas simétricas de la camisa a partir de la máscara compensada. ")
    
    p.mb-4 Las piezas se unen en las zonas del empeine y del talón utilizando cinta de enmascarar, asegurando un ajuste firme que permita dar forma a la camisa sobre la horma.

    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 15.
          span Unión de piezas de la camisa sobre la horma
        figure
          img(src="@/assets/curso/temas/tema2/8.png", data-aos="zoom-in", alt="Unión de las piezas recortadas de la camisa sobre la horma con cinta adhesiva. ")
    
    p.mb-4 La camisa se arruga ligeramente para facilitar su colocación sobre la horma, lo que permite que se adapte mejor a su forma durante el proceso de ajuste.

    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 16.
          span Adaptación de la camisa a la horma
        figure
          img(src="@/assets/curso/temas/tema2/9.png", data-aos="zoom-in", alt="Proceso de adaptación de la camisa arrugada sobre la horma para mayor ajuste.  ")
    
    p.mb-4 Se verifica que la camisa ajuste correctamente sobre la horma, realizando los ajustes necesarios para asegurar que se adapte con precisión a su forma y contorno.

    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 17.
          span Verificación del ajuste de la camisa
        figure
          img(src="@/assets/curso/temas/tema2/10.png", data-aos="zoom-in", alt="Verificación del ajuste preciso de la camisa sobre la horma. ")
    
    p.mb-4 Finalmente, se obtiene el perfil de la horma, el cual servirá como base para la elaboración precisa del molde patrón.

    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 18.
          span Perfil de la horma como base del molde patrón
        figure
          img(src="@/assets/curso/temas/tema2/11.png", data-aos="zoom-in", alt="Perfil final de la horma obtenido a partir de la camisa. ")

    p.mb-4 Una vez compensada la máscara, se dibuja sobre una cartulina incluyendo los puntos y líneas guía, como se presenta en la imagen.

    .row.mb-5.justify-content-center.align-items-center.bg-color-20.p-5
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 19.
          span Dibujo de la máscara compensada sobre cartulina
        figure
          img(src="@/assets/curso/temas/tema2/12.png", data-aos="zoom-in", alt="Máscara compensada dibujada sobre cartulina con puntos y líneas guía. ")

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

<style lang="sass"></style>
