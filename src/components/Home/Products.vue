<template>
  <v-row class="mb-16">
    <v-col cols="12" class="text-center">
      <h2 class="playball">¿En qué Podemos Ayudarte?</h2>
    </v-col>
    <v-col>
        <img src="../../assets/1.jpg" alt="Alto relieve" height="250">
        <p>Alto relieve</p>
    </v-col>
    <v-col>
        <img src="../../assets/1.jpg" alt="Facturas autorizadas por el SENIAT" height="250">
        <p>Facturas autorizadas por el SENIAT</p>
    </v-col>
    <v-col>
        <img src="../../assets/1.jpg" alt="Alto relieve" height="250">
        <p>Tarjetas de boda, bautizo y Bar Mitzvah</p>
    </v-col>
    <v-col cols="12" class="mt-5 text-center">
      <v-btn class="py-6" color="#EFB810" to="/services">Todos nuestros servicios<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
    </v-col>
  </v-row>
</template>

<script>
export default {
    name: 'Products'
}
</script>

<style scoped>
h2
{
  font-size: 3.5rem;
}

p
{
    margin-top: 20px;
    font-weight: 600;
    font-size: 1.1em;
}
</style>