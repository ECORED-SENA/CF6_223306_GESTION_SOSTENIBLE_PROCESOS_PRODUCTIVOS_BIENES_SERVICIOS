<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1(data-aos="fade-right") Introducción

    .row.align-items-center.mb-4
      .col-lg-8(data-aos="fade-left")
        p En la actualidad los mercados son cada vez más competitivos, ya que la tecnología y globalización ha permitido que empresas de todo el mundo puedan ingresar a cualquier mercado, es por ello que las organizaciones debe generar cambios constantes en sus modelos de negocio y productos para renovarse constantemente de acuerdo con las nuevas tendencias del mercado y consumidor. 
        p Para lograr estos cambios tecnológicos de manera constante      es necesario implementar una cultura de la innovación, en la cual se debe realizar de forma periódica un diagnóstico de su situación actual, con el fin de generar propuestas de innovación, las cuales deberán ser evaluadas de acuerdo a las políticas organizaciones y recursos disponibles.
        p En este componente formativo, aprenderás con un enfoque en la producción de bienes y servicios sostenibles, a elaborar propuesta de alternativas de innovación para una organización, así como también la forma de evaluar dichas propuestas de acuerdo con      un análisis financiero y políticas organizacionales.
      .col-lg-4
        figure(data-aos="fade-right")
          img.img-t.m-auto(src='@/assets/curso/introduccion/img01.svg')

    p La metodología del componente es teórico-     práctica, ya que se contextualiza al lector con definiciones y explicaciones de casos prácticos, a los cuales se les profundizará con videos multimedia por medio de los llamados de acción, culminando con actividades prácticas para validar el conocimiento, como lo es un taller de relacionamiento de conceptos y una guía de aprendizaje. Antes de iniciar el estudio de este componente, te invitamos a observar el siguiente video:

    figure
    .video
      iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)



    
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
