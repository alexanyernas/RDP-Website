<template>
  <div>
    <Presentation 
      title="Sobre Nosotros"
      subtitle="Conoce mucho más de nuestra historia y de todas aquellas cosas que tenemos para ofrecerte al elegirnos."
    />
    <v-row class="mb-16">
      <v-col class="ml-16">
        <img src="../assets/16.jpg" alt="16">
      </v-col>  
      <v-col class="col-blue">
        <h2>Somos la opción perfecta a elegir para ti</h2>
        <p>Con toda nuestra experiencia y dedicación, buscamos que cada cliente quede contento al momento de la entrega de los trabajos a realizar.</p>
      </v-col>  
    </v-row>
    
    <v-row>
      <v-col>
        <h2>Nuestra misión</h2>
        <p>Nos enfocamos en el buen desarrollo de cada uno de los proyectos a realizar para así crear una confianza y fidelidad con cada cliente para satisfacer cada una de las necesidades que pueda llegar a presentar con aquellas cosas que te gusaría que nosotros desarrolláramos.</p>
      </v-col>  
      <v-col>
        <h2>Te aseguramos...</h2>
        <v-list>
          <v-list-item><v-icon>mdi-check-circle</v-icon> Compromiso en cada proyecto</v-list-item>
          <v-list-item><v-icon>mdi-check-circle</v-icon> Excelencia en la presentación</v-list-item>
          <v-list-item><v-icon>mdi-check-circle</v-icon> Satisfacción con cada resultado</v-list-item>
        </v-list>
      </v-col>  
    </v-row>
    
    <v-row class="mb-16">
      <v-col class="col-black"> 
        <h2>¿Por qué elegirnos?</h2>
        <p>Te ofrecemos muchas más razones de porqué no debes dudar en comunicarte con nosotros para realizar tus proyectos.</p>
        <v-list>
          <v-list-item><v-icon color="#EFB810">mdi-check-circle</v-icon> Atención totalmente exclusiva</v-list-item>
          <v-list-item><v-icon color="#EFB810">mdi-check-circle</v-icon> Respuestas al instante</v-list-item>
          <v-list-item><v-icon color="#EFB810">mdi-check-circle</v-icon> Calidad en el desarrollo</v-list-item>
          <v-list-item><v-icon color="#EFB810">mdi-check-circle</v-icon> Experiencia en el área</v-list-item>
          <v-list-item><v-icon color="#EFB810">mdi-check-circle</v-icon> Precios competitivos</v-list-item>
        </v-list>
      </v-col>  
      <v-col>
        <img src="../assets/16.jpg" height="320" alt="16">
      </v-col>  
    </v-row>
  </div>
</template>

<script>
import Presentation from '../components/Presentation.vue'

export default {
  name: 'About',
  components: {
    Presentation
  }
}
</script>

<style scoped>
.col-blue,
.col-black
{
  color: #FFF
}

.col-blue
{
  background-color: #133369;
}

.col-black
{
  background-color: #000;
}
</style>