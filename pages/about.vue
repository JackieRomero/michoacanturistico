<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />

        <v-row no-gutters>
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="paricutin.jpg"
              lazy-src="pexels-canva-studio-3277806.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                Volcán Paricutín
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              ></h3>
              <p>
                El volcán más joven de la historia es uno de los principales
                lugares turísticos de México, por ser considerado una maravilla
                natural del mundo con una elevación de 2800 metros.
              </p>
              <p>
                Luego de su erupción en febrero de 1943, tuvo actividad durante
                nueve años y sepultó dos pueblos: Paricutín, de donde proviene
                su nombre, y San Juan Parangaricutiro, lugar en el que solo
                sobrevivió la torre de una iglesia, cuyas ruinas puedes visitar
                de manera gratuita por aproximadamente 1 dólar, que equivale a
                25 pesos mexicanos, así puedes conocer el volcán en Michoacán.
              </p>
              <p>
                Existen dos opciones para llegar. Por una parte hay dos
                aparcamientos al pie del volcán, por lo que deberás hacer un
                recorrido durante una o dos horas. Y si no tienes carro puedes
                dirigirte en autobús hasta la parada más cercana en Angahuan.
                Con esta alternativa debes tener buenas condiciones físicas,
                llevar mucha agua y ropa cómoda, porque la caminata dura cinco
                horas aproximadamente.
              </p>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="camecuaro.jpg"
              lazy-src="pexels-rfstudio-3810792.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                Lago de Camecuaro
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              ></h3>
              <p>
                Es un parque natural conocido en todo el país por ser un portal
                para entrar en contacto directo con la naturaleza. Si eres
                amante de los deportes, entonces te encantará practicar natación
                en sus albercas de aguas termales, acampar o dar un paseo en
                lancha. El Parque Nacional Lago de Camécuaro es un lugar
                adecuado para todas las edades, así que no dudes en visitarlo
                por el costo de menos de un dólar por persona, con más
                exactitud, unos 15 pesos mexicanos.
              </p>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="mariposa.jpg"
              lazy-src="pexels-rfstudio-3810792.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                Santuario de la Mariposa Monarca
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              ></h3>
              <p>
                Entre los lugares turísticos en Michoacán recomendados, encabeza
                la lista la Reserva de la Biósfera de la Mariposa Monarca, donde
                probablemente vivirás la experiencia más cercana a un cuento de
                hadas. Entre los meses de noviembre y marzo las Mariposas
                Monarcas emigran hacia México, en Michoacán. Así que si te
                encuentras durante esa temporada en el país, no dudes en pasear
                por tan maravilloso lugar, declarado Patrimonio Natural de la
                Humanidad desde 2008. Son cinco los santuarios que conforman
                Reserva Natural de la Mariposa Monarca y dos de ellos se
                encuentran en Michoacán: El Rosario y Sierra Chincua. En el
                primero no puedes perder la oportunidad de ir hasta la cúspide
                de la montaña, el sitio de hibernación de las mariposas, por
                2,35 dólares, equivalentes a 45 pesos mexicanos.
              </p>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="catedralmorelia.jpg"
              lazy-src="pexels-rfstudio-3810792.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                Catedral de Morelia
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              ></h3>
              <p>
                Un lugar lleno de historia, donde disfrutarás de una rica
                gastronomía, y admirarás su arquitectura, comenzando con la
                Catedral de Morelia, uno de los sitios culturales de Michoacán.
                El estilo barroco la convierte en un delirio para visitantes y
                lugareños, y su cúpula de oro junto a los vitrales italianos
                deslumbran a cualquiera. Organiza tu agenda turística michoacana
                y marca a las 8:45 pm tu visita a la Catedral para que disfrutes
                de los momentos más especiales en ella.
              </p>
            </div>
          </v-col>
        </v-row>
        <SectionsTimeline />
      </v-col>
    </v-row>
  </section>
</template>

<script>
export default {
  data() {
    return {
      heroAlt: [
        {
          src: 'pexels-moose-photos-1036641.jpg',
          heading: ' About Us ',
        },
      ],
      ourTeam: [
        {
          name: 'John Churchill',
          position: 'Marketing Director',
          phone: '+1 (987) 1625346',
          email: 'john@example.com',
          photo: 'person-1.jpg',
        },
        {
          name: 'Fiona	Ross',
          position: 'Project Manager',
          phone: '+1 (987) 5894684',
          email: 'fiona@example.com',
          photo: 'person-2.jpg',
        },
        {
          name: 'Justin	Rees',
          position: 'VP Marketing',
          phone: '+1 (987) 6982456',
          email: 'justin@example.com',
          photo: 'person-3.jpg',
        },
        {
          name: 'Amelia	Ogden',
          position: 'Communication Manager',
          phone: '+1 (987) 6982456',
          email: 'amelia@example.com',
          photo: 'person-4.jpg',
        },
        {
          name: 'Sebastian Bailey',
          position: 'Advertising Director',
          phone: '+1 (987) 6982456',
          email: 'sebastian@example.com',
          photo: 'person-5.jpg',
        },
        {
          name: 'Eric Sutton',
          position: 'Advertising Executive',
          phone: '+1 (987) 6982456',
          email: 'audrey@example.com',
          photo: 'person-6.jpg',
        },
        {
          name: 'Xia Yen',
          position: 'Advertising Manager',
          phone: '+1 (987) 6982456',
          email: 'christian@example.com',
          photo: 'person-7.jpg',
        },
        {
          name: 'Bernadette	Springer',
          position: 'Employee Relations Manager',
          phone: '+1 (987) 6982456',
          email: 'bernadette@example.com',
          photo: 'person-8.jpg',
        },
        {
          name: 'Elizabeth Newman',
          position: 'Project Manager',
          phone: '+1 (987) 6982456',
          email: 'elizabeth@example.com',
          photo: 'person-9.jpg',
        },
      ],
    }
  },
  head() {
    return {
      title: 'About Us',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem',
        },
      ],
    }
  },
}
</script>
