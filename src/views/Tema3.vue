<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Estado de mercancías

    .col-lg-12.xl-10.mb-5.color-custom-1
      .bloque-texto-g.p-3.p-sm-4.p-md-5.mb-5.color-blue-1
        .bloque-texto-g__texto.p-4
          b(style="color: #214BE5;") 
          p.mb-0 Las mercancías en su proceso de distribución pasan por diferentes procesos hasta la entrega que se hace a su destinario, en este proceso se tienen en cuenta los siguientes elementos que permiten abordar el estado de la mercancía. 
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/Images/tema3/img_1.png')})`}"
        )

    Separador 
    
    #t_3_1.titulo-segundo
      .h2  3.1  Manipulación de alimentos

    .row.justify-content-center.align-items-center.mb-5    
      .col-auto.onTop
        img(src="@/assets/curso/Images/tema3/img_2.png" alt='', style="width:430px; display:block; margin:0 auto;")   
      .col-lg-6
        .custom_box_left_2     
          p Proceso que involucra el contacto directo con alimentos durante la transformación, envasado, almacenamiento, transporte y distribución.

    p.mb-5 Planear y llevar cabo una adecuada distribución de la mercancía, conlleva a todo un proceso para la planeación, ejecución y control de los productos almacenados, para ello en el siguiente video se comparten algunos referentes que soportan la logística para la distribución de alimentos. 

    figure.mb-5
    .video
      iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    br
    br
    .row.justify-content-center.mb-5
      ImagenInfografica.color-secundario.mb-3
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/Images/tema3/img_3.svg', alt='', style="width:830px; display:block; margin:0 auto;")
    
        .tarjeta.color-acento-botones.p-3(x="11%" y="52%" numero="")
          .h5.mb-2 Materias primas

        .tarjeta.color-acento-botones.p-3(x="25%" y="100%" numero="")
          .h5.mb-2 Productos intermedios

        .tarjeta.color-acento-botones.p-3(x="49%" y="100%" numero="")
          .h5.mb-2 Productos terminados

        .tarjeta.color-acento-botones.p-3(x="72%" y="100%" numero="")
          .h5.mb-2 De accesorios

        .tarjeta.color-acento-botones.p-3(x="86%" y="52%" numero="")
          .h5.mb-2 De refracción
    p.mb-3 <b>Recepción de mercancías, cargue, descargue, traslados</b>
    .col-lg-12.mx-auto.mb-5
      .bloque-texto-g.color-custom-2.p-3.p-sm-4.p-md-5.mb-5
        .bloque-texto-g-1__img(
          :style="{'background-image': `url(${require('@/assets/curso/Images/tema3/img_4.png')})`}"
        )
        .bloque-texto-g-1__texto.p-4
          p.mb-3 En un depósito logístico, la recepción de mercancías es la transferencia o aceptación en custodia de un producto o casa, entregado por un productor o vendedor, para que este sea trasladado hasta un cliente destinatario, en un tiempo estipulado y bajo las condiciones requeridas para la manipulación del producto.  

          P El cargue de mercancías es la disposición de la mercancía en el vehículo que la transporta al destino, este proceso debe asegurar aspectos como una adecuada distribución del peso en la unidad de transporte y que la mercancía cargada si este asignada en la ruta que sigue el automotor. ue, de manera simultánea, invita a las personas a agregar valor desde sus puestos de trabajo. 

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
