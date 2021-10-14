<template>
  <v-container class="mt-16">
    <v-row>
      <v-col cols="12" xs="12" lg="3">
        <div>
          <h3 class="mb-6">Relieves Del Pozo</h3>
          <h5>Dirección</h5>
          <p>Cl. Tiuna, Edificio Tony, Piso 1, Local A, Urbanización Boleita, Caracas, Distrito Capital, Gran Caracas, Venezuela.</p>
          <h5 class="mt-10">Llámanos</h5>
          <p>+58 212 238 4094</p>
        </div>
      </v-col>
      
      <v-col cols="12" xs="12" lg="3">
        <h4 class="mb-6">Horarios de atención</h4>
        <div>
          <p class="mb-1">Lunes: 7.00 am - 3.30 pm</p>
          <p class="mb-1">Martes: 7.00 am - 3.30 pm</p>
          <p class="mb-1">Miércoles: 7.00 am - 3.30 pm</p>
          <p class="mb-1">Jueves: 7.00 am - 3.30 pm</p>
          <p class="mb-1">Viernes: 7.00 am - 3.30 pm</p>
        </div>
        <div class="mt-8">
          <v-btn
            href="#"
            target="_BLANK"
            rel="noopener noreferrer"
            fab
            elevation="2"
            class="mr-2"
          >
            <v-icon color="#000" class="icon">mdi-facebook</v-icon>
          </v-btn>
          <v-btn
            href="#"
            target="_BLANK"
            rel="noopener noreferrer"
            fab
            elevation="2"
            class="mr-2"
          >
            <v-icon color="#000" class="icon">mdi-instagram</v-icon>
          </v-btn>
          <v-btn
            href="#"
            target="_BLANK"
            rel="noopener noreferrer"
            fab
            elevation="2"
          >
            <v-icon color="#000" class="icon">mdi-whatsapp</v-icon>
          </v-btn>
        </div>
      </v-col>
      
      <v-col cols="12" xs="12" lg="6">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7846.104171585546!2d-66.82593117569614!3d10.496560370047288!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8c2a59d1fdcea6eb%3A0x930fc4b4477f0c40!2sBole%C3%ADta%20Norte%2C%20Caracas%201071%2C%20Miranda!5e0!3m2!1ses-419!2sve!4v1634156398463!5m2!1ses-419!2sve" width="550" height="320" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </v-col>
    </v-row>
    <v-row class="mt-15">
      <p>© {{ new Date().getFullYear() }} Relieves Del Pozo. Todos los derechos reservados.</p>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
.icon
{
  font-size: 2.25em;
}
</style>