<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-5 Bienvenidos a este programa de aprendizaje, donde se exploraran los metales más utilizados en el gremio joyero y los conceptos fundamentales de la joyería y la metalurgia. A lo largo de este curso, se descubrirá cómo la metalurgia no solo se relaciona con aspectos técnicos, sino que también está profundamente entrelazada con la cultura, la economía y la organización social de las comunidades joyeras en Colombia. se analizaran las propiedades de los metales, su identificación y las conversiones más comunes en la creación de joyas, así como los distintos tipos de joyería que han evolucionado a lo largo del tiempo. A través de este viaje se exploraran conceptos conjuntos entre la tradición, el diseño y el arte manifestados en la joyería. Bienvenido a este componente formativo:

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/O4BuDDCUxnI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Fuente: Sena 2024.
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
