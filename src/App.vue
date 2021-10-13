<template>
  <v-app>
    <NavBar />
    <MenuSocials />
    <v-main>
      <router-view />
      <Footer />
    </v-main>
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
</style>
