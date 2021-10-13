<template>
  <div>
    <Presentation 
      title="Nuestros Servicios"
      subtitle="Conoce sobre todos aquellos servicios que tenemos para nuestra distinguida clientela y así decidir cuál te gustaría elegir para tus ideas."
    />
    <Products />
  </div>
</template>

<script>
import Presentation from '../components/Presentation.vue'
import Products from '../components/Services/Products.vue'

export default {
  name: 'Services',
  components: {
    Presentation,
    Products
  }
}
</script>