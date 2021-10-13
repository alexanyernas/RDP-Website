<template>
  <v-container>
    
    <v-row>
      <v-col>
        <h1 class="playball">Presencia en la Impresión, es Nuestra Excelencia</h1>
        <v-btn color="#EFB810" to="/about">Conoce sobre nosotros<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
      </v-col>
      
      <v-col>
        <img src="../assets/8.jpg" alt="8">
      </v-col>
    </v-row>

    <v-row class="mt-15">
      <v-col>
        <img src="../assets/10.jpg" alt="10">
      </v-col>
      
      <v-col>
        <h4>¿Quiénes Somos?</h4>
        <p>
          Somos una empresa dedicada a las artes gráficas con más de 20 años de experiencia en el mercado. 
          Destacamos nuestro compromiso con cada uno de los trabajos a realizar y procuramos complacer todas 
          las expectativas que los clientes aspiran al solicitar los servicios que ofrecemos.
        </p>
        <v-btn color="#EFB810" to="/contact">Solicita un Presupuesto<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
      </v-col>
    </v-row>

    <v-row class="mt-15">
      <v-col cols="12" class="text-center">
        <h2>¿En qué Podemos Ayudarte?</h2>
      </v-col>
      
      <v-col>
        <img src="../assets/1.jpg" alt="1" width="350">
        <p>Alto relieve</p>
      </v-col>
      
      <v-col>
        <img src="../assets/2.jpg" alt="2" width="350">
        <p>Tarjetas de boda, bautizo y Bar Mitzvah</p>
      </v-col>
      
      <v-col>
        <img src="../assets/3.jpg" alt="3" width="350">
        <p>Estampación</p>
      </v-col>

      <v-col cols="12" class="text-center">
        <v-btn color="#EFB810" to="/services">Todos nuestros servicios<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
      </v-col>
    </v-row>

    <v-row class="mt-15">
      <v-col>
        <img src="../assets/6.jpg" alt="6" width="400">
      </v-col>
      <v-col>
        <h2 class="playball">Nos Encargamos de Hacer Realidad tus Ideas</h2>
        <v-btn color="#EFB810">Solicita un Presupuesto<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
      </v-col>
    </v-row>

    <v-row class="mt-15">
      <v-col cols="12">
        <h2>La Opinión de Nuestros Clientes</h2>
      </v-col>
      
      <v-col>

      </v-col>
      
      <v-col>

      </v-col>
      
      <v-col>

      </v-col>
    </v-row>

    <v-row class="mt-15">
      <v-col cols="12" class="text-center">
        <h2 class="playball">Nuestro Trabajo</h2>
      </v-col>
      <v-col
        v-for="n in 9"
        :key="n"
        class="d-flex child-flex"
        cols="4"
      >
        <v-img
          :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
          :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
          aspect-ratio="1"
          class="grey lighten-2"
          height="300"
        >
          <template v-slot:placeholder>
            <v-row
              class="fill-height ma-0"
              align="center"
              justify="center"
            >
              <v-progress-circular
                indeterminate
                color="grey lighten-5"
              ></v-progress-circular>
            </v-row>
          </template>
        </v-img>
      </v-col>
    </v-row>

  </v-container>
</template>

<script>
export default {
  name: 'Home'
}
</script>
