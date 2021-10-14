<template>
    <v-row class="mb-16">
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
          src="../../assets/10.jpg"
          aspect-ratio="1"
          class="grey lighten-2"
          height="300"
        >
        </v-img>
      </v-col>
    </v-row>
</template>

<script>
export default {
    name: 'Work'
}
</script>

<style scoped>
h2
{
  font-size: 3.5rem;
}
</style>