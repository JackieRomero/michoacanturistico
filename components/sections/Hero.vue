<template>
  <section id="hero">
    <v-carousel
      height="calc(100vh - 64px)"
      dark
      cycle
      show-arrows-on-hover
      draggable="true"
      hide-delimiter-background
    >
      <v-carousel-item
        v-for="(carousel, carindex) in carouselsData"
        :key="carindex"
        :src="carousel.src"
        class="gradient-fill"
      >
        <v-container fill-height>
          <div style="max-width: 600px">
            <div class="text-md-h2 mb-3 text-sm-h3 text-h5 font-weight-black">
              {{ carousel.heading.toUpperCase() }}
            </div>
            <p class="mb-5">{{ carousel.subHeading }}</p>

            <span class="mx-2 my-4"></span>
          </div>
        </v-container>
      </v-carousel-item>
    </v-carousel>
  </section>
</template>

<script>
export default {
  data() {
    return {
      carouselsData: [
        {
          src: 'index.jpg',
          heading: '  Michoacan Turistico',
          subHeading:
            'Michoacán es uno de los maravillosos lugares turísticos de México por sus riquezas naturales, sus milenarias tradiciones indígenas y manifestaciones artísticas. Este estado, conocido como el Alma de México, ofrece una gran variedad gastronómica, festivales culturales y diversas opciones de alojamiento, desde hoteles modernos hasta los de estilo colonial, para que te des unas merecidas vacaciones. ',
        },
        {
          src: 'index.jpg',
          heading: ' Michoacan Turistico',
          subHeading:
            'Michoacán es uno de los maravillosos lugares turísticos de México por sus riquezas naturales, sus milenarias tradiciones indígenas y manifestaciones artísticas. Este estado, conocido como el Alma de México, ofrece una gran variedad gastronómica, festivales culturales y diversas opciones de alojamiento, desde hoteles modernos hasta los de estilo colonial, para que te des unas merecidas vacaciones.',
        },
      ],
    }
  },
}
</script>

<style>
.gradient-fill .v-responsive__content {
  background: rgb(0, 0, 0);
  background: linear-gradient(
    to right,
    rgba(3, 12, 41, 0.75),
    rgba(5, 11, 31, 0.65)
  );
}
</style>
