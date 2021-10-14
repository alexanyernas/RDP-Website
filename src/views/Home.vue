<template>
  <div>
    <HeroImage />
    <v-container>
      <AboutUs />
      <Products />
    </v-container>
    <Slogan />
    <v-container>
      <Clients />
      <Work />
    </v-container>
  </div>
</template>

<script>
import HeroImage from '../components/Home/HeroImage.vue'
import AboutUs from '../components/Home/AboutUs.vue'
import Products from '../components/Home/Products.vue'
import Slogan from '../components/Home/Slogan.vue'
import Clients from '../components/Home/Clients.vue'
import Work from '../components/Home/Work.vue'

export default {
  name: 'Home',
  components: {
    HeroImage,
    AboutUs,
    Products,
    Slogan,
    Clients,
    Work
  }
}
</script>
