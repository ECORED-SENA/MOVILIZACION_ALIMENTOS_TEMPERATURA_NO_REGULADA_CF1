<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Estado de mercancías

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/Images/tema3/img_1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las mercancías en su proceso de distribución pasan por diferentes procesos hasta la entrega que se hace a su destinario, en este proceso se tienen en cuenta los siguientes elementos que permiten abordar el estado de la mercancía.   

    Separador 
    
    #t_3_1.titulo-segundo
      .h2  3.1  Manipulación de alimentos

    .row.justify-content-center.align-items-center.gx-0.mb-5    
      .col-auto.onTop
        img(src="@/assets/curso/Images/tema3/img_2.png" alt='', style="width:430px;").m-auto   
      .col-lg-6
        .custom_box_left_2     
          p Proceso que involucra el contacto directo con alimentos durante la transformación, envasado, almacenamiento, transporte y distribución.

    p.mb-5 Planear y llevar cabo una adecuada distribución de la mercancía, con lleva a todo un proceso para la planeación, ejecución y control de los productos almacenados, para ello en el siguiente video se comparten algunos referentes que soportan la logística para la distribución de alimentos.    

    figure.mb-5
    .video
      <iframe width="560" height="315" src="https://www.youtube.com/embed/vR4nPjSUB0w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    br
    br

    h3 Tipos de almacenamiento y principios de almacenamiento
    p.mb-5 Al realizar una adecuada logística del almacenamiento la empresa logra una operación eficiente, posibilita el acceso a las mercancías reduciendo traslados y se aprovecha la capacidad de bodegaje. Los tipos de almacenamiento que encontramos en logística son:

    .crd-gray.pt-5
      .row.justify-content-center.my-5
        .col-lg-10.mb-5
          ImagenInfografica.color-secundario
            template(v-slot:imagen)
              figure.m-0
                img(src='@/assets/curso/Images/tema3/img_3.svg', alt='')        
        
            .tarjeta.color-acento-botones.p-3(x="0%" y="52%" numero="")
              .h5.mb-2 Materias primas
              p.mb-0 Son los productos pertenecientes al nivel primario en el sector de la producción, son elementos en estado puro, es decir que no han sufrido transformación alguna.

            .tarjeta.color-acento-botones.p-3(x="18%" y="97%" numero="")
              .h5.mb-2 Productos intermedios
              p Son los productos que han presentado alguna modificación, pero aún se encuentran en etapa de producción.

            .tarjeta.color-acento-botones.p-3(x="48%" y="97%" numero="")
              .h5.mb-2 Productos terminados
              p.mb-0 El almacenaje de estos productos requiere más atención, este se deriva de las características del producto y las condiciones que requiera para la conservación; se debe tener en cuenta para el almacenaje aspectos como luz, temperatura y ciclos. La manipulación y transporte también deben ser bajo las condiciones definidas por el cliente o remitente.

            .tarjeta.color-acento-botones.p-3(x="79%" y="97%" numero="")
              .h5.mb-2 Accesorios
              p.mb-0 Es el almacenaje de productos que se requieren para complementar una producción.

            .tarjeta.color-acento-botones.p-3(x="96%" y="52%" numero="")
              .h5.mb-2 De refracción
              p.mb-0 Este tipo de almacenamiento se ocupa de las partes o refracciones y que generalmente son elementos utilizados para reparar productos que han sido usados por clientes, se aplica en la etapa de postventa, para cubrir garantías.

      .row.justify-content-center
        .col-lg-11.mb-5
          p.mb-3 <b>Recepción de mercancías, cargue, descargue, traslados</b>
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/Images/tema3/img_4.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p En un depósito logístico, la recepción de mercancías es la transferencia o aceptación en custodia de un producto o cosa, entregado por un productor o vendedor, para que este sea trasladado hasta un cliente destinatario, en un tiempo estipulado y bajo las condiciones requeridas para la manipulación del producto. 
              br
              br
              P El cargue de mercancías es la disposición de la mercancía en el vehículo que la transporta al destino, este proceso debe asegurar aspectos como una adecuada distribución del peso en la unidad de transporte y que la mercancía cargada si este asignada en la ruta que sigue el automotor. 

    

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
