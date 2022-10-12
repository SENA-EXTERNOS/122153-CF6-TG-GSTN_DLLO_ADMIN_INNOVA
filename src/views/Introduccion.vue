<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row
      .col-12.mb-5
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style='{ "background-image": `url(${require("@/assets/template/introduccion/t0-i1.jpg")})` }'
          )
          .bloque-texto-g__texto.p-4
            strong.mb-0.color_texto_acento Apreciado aprendiz, bienvenido a este componente formativo, 
            | donde afianzará los conocimientos relacionados con la gestión archivística, de tal manera que logre conocer su transformación, y reconozca la importancia de este proceso en el funcionamiento normal de las organizaciones.
      .col-12.mb-5
        p Para conocer la importancia de la historia de los archivos en la sociedad se invita a ver el siguiente video:
      .col-12.mb-5
        figure
          .video
            iframe(
              width='560',
              height='315',
              src='https://www.youtube.com/embed/2L91WMqw96A',
              title='YouTube video player',
              frameborder='0',
              allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture',
              allowfullscreen
            )
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
