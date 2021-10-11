<template>
  <v-app>
    <NavBar />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import NavBar from './components/NavBar.vue'
import MenuSocials from './components/MenuSocials.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    MenuSocials
  }
}
</script>
