<template>
  <section id="intro" class="py-16">
    <v-container>
      <v-responsive class="max-auto mx-auto text-center" max-width="600">
        <v-avatar color="primary" size="70" class="mb-8">
          <v-icon x-large dark>mdi-web</v-icon>
        </v-avatar>
        <h2 class="text-h4 text-md-h3 text-center font-weight-black mb-7">
          Origen
        </h2>
        <p class="title font-weight-light">
          <strong>Michoacan</strong>
          oficialmente llamado Estado Libre y Soberano de Michoacán de Ocampo,
          El vocablo Mich-huah-can se forma con la raíz o radical del vocablo
          michin, pescado, que en la escritura fonética se señala con un
          pescado; la partícula -huah, posesivo calificativo de lugar, y la
          terminación -can, lugar (en la escritura fonética, se señala con un
          cerro). El estado de Michoacán se ubica en el centro-oeste del
          territorio mexicano. Limita al norte con los estados de Guanajuato y
          Querétaro, al este con el estado de México, al sur con Guerrero al
          suroeste con el océano Pacífico y el noroeste con Colima y Jalisco.
          Cubre una superficie de 58,585 km², que representa el 3% de la
          superficie total del país, ocupando el lugar número 16 en extensión
          entre las 32 entidades federativas de México.
        </p>
      </v-responsive>

      <v-row class="pt-12">
        <v-col v-for="card in cards" :key="card.title" cols="12" md="4">
          <v-row no-gutters>
            <v-col :cols="card.callout ? 9 : 12">
              <div class="pr-2">
                <div class="text--disabled" v-text="card.subtitle"></div>
                <h4
                  class="text-uppercase mt-1 mb-4"
                  style="letter-spacing: 0.15em"
                  v-text="card.title"
                ></h4>
                <p v-text="card.text"></p>
              </div>
            </v-col>
            <v-col v-if="card.callout" cols="2">
              <span
                class="text-h3 grey--text font-weight-bold pr-8"
                style="opacity: 0.1"
                >{{ card.callout }}</span
              >
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  data() {
    return {
      cards: [],
    }
  },
}
</script>
