<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción 

    p.mb-5 La movilización de los diferentes tipos de mercancías, generan procesos para esta llegue en óptimas condiciones a sus destinatarios, en este componente se reconocen algunos elementos que deben tenerse presente para que este proceso se lleve de forma adecuada, confiable y responda a las necesidades de sus destinatarios, para comenzar con las temáticas propuestas en este componente, se debe revisar la siguiente introducción. 

    figure.mb-5
    .video
      <iframe width="560" height="315" src="https://www.youtube.com/embed/SrYgf2fVnbw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      
    br
    p.mb-0 Ahora, se puede avanzar con el desarrollo de las temáticas propuestas. 
    

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
