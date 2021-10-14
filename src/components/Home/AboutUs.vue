<template>
    <v-row class="mb-16">
      <v-col>
        <img src="../../assets/10.jpg" alt="10">
      </v-col>
      <v-col class="my-auto">
        <h4 class="mb-4">¿Quiénes Somos?</h4>
        <p>
          Somos una empresa dedicada a las artes gráficas con más de 20 años de experiencia en el mercado. 
          Destacamos nuestro compromiso con cada uno de los trabajos a realizar y procuramos complacer todas 
          las expectativas que los clientes aspiran al solicitar los servicios que ofrecemos.
        </p>
        <v-btn class="py-6 mt-10" color="#EFB810" to="/contact">Solicita un Presupuesto<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
      </v-col>
    </v-row>
</template>

<script>
export default {
    name: 'AboutUs'
}
</script>

<style scoped>
h4
{
  font-size: 2em;
}
</style>