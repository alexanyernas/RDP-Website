<template>
    <v-row class="mb-16 px-16 row">
      <v-col class="py-0">
        <img src="../../assets/6.jpg" alt="6" width="500" height="100%">
      </v-col>
      <v-col class="my-auto">
        <h2 class="mb-10 playball">Nos Encargamos de Hacer Realidad tus Ideas.</h2>
        <v-btn color="#EFB810" class="py-6" to="/contact">Solicita un Presupuesto<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
      </v-col>
    </v-row>
</template>

<script>
export default {
    name: 'Slogan'
}
</script>

<style scoped>
.row
{
  background-color: #133369;
  color: #FFF;
}

h2
{
  font-weight: 500;
  font-size: 3rem;
}
</style>