<template>
  <v-app>
    <NavBar />
    <v-main>
      <router-view />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Footer
  }
}
</script>

<style>
*
{
  font-family: 'Work Sans', sans-serif;
}

.playball
{
  font-family: 'Playball', cursive;
}

::-webkit-scrollbar 
{
  width: .6rem;
  border-radius: .5rem;
}
::-webkit-scrollbar-thumb 
{
  background-color: #EFB810;
  border-radius: .5rem;
}
::-webkit-scrollbar-thumb:hover
{
  background-color: #1E88E5;
}

</style>
