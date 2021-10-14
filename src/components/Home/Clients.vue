<template>
    <v-row class="mb-16">
      <v-col cols="12" class="text-center">
        <h2 class="playball">La Opinión de Nuestros Clientes</h2>
      </v-col>
      
      <v-col>
        <v-card
          class="mx-auto"
          color="#000"
          dark
          max-width="400"
        >
          <v-card-title>
            <v-rating
              :value="5"
              color="amber"
              dense
              half-increments
              readonly
              size="24"
            ></v-rating>
          </v-card-title>

          <v-card-text class="text-h5 font-weight-bold">
            "Aunque no lo diga, agradezco todos los días de que sean mi familia y los adoro".
          </v-card-text>

          <v-card-actions>
            <v-list-item class="grow">
              <v-list-item-avatar color="grey darken-3">
                <v-img
                  class="elevation-6"
                  src="../../assets/person.jpg"
                ></v-img>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title>Alexanyer Naranjo</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-card-actions>
        </v-card>
      </v-col>
      
      <v-col>
        <v-card
          class="mx-auto"
          color="#133369"
          dark
          max-width="400"
        >
          <v-card-title>
            <v-rating
              :value="5"
              color="amber"
              dense
              half-increments
              readonly
              size="24"
            ></v-rating>
          </v-card-title>

          <v-card-text class="text-h5 font-weight-bold">
            "La atención al cliente es buena y feliz con cada trabajo hecho por la empresa".
          </v-card-text>

          <v-card-actions>
            <v-list-item class="grow">
              <v-list-item-avatar color="grey darken-3">
                <v-img
                  class="elevation-6"
                  src="../../assets/person.jpg"
                ></v-img>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title>Eren Jaeger</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-card-actions>
        </v-card>
      </v-col>
      
      <v-col>
        <v-card
          class="mx-auto"
          color="#000"
          dark
          max-width="400"
        >
          <v-card-title>
            <v-rating
              :value="5"
              color="amber"
              dense
              half-increments
              readonly
              size="24"
            ></v-rating>
          </v-card-title>

          <v-card-text class="text-h5 font-weight-bold">
            "Relieves Del Pozo, excelencia en su totalidad con cada proyecto realizado con ellos".
          </v-card-text>

          <v-card-actions>
            <v-list-item class="grow">
              <v-list-item-avatar color="grey darken-3">
                <v-img
                  class="elevation-6"
                  src="../../assets/person.jpg"
                ></v-img>
              </v-list-item-avatar>

              <v-list-item-content>
                <v-list-item-title>Naruto Uzumaki</v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
</template>

<script>
export default {
    name: 'Clients'
}
</script>

<style scoped>
h2
{
  font-size: 3.5rem;
}
</style>