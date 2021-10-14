<template>
  <div>
    <Presentation 
      title="Contáctanos"
      subtitle="No pierdas la oportunidad de disfrutar de nuestros servicios para realizar esas tarjetas o presentaciones que tanto te gustaría que fuesen llevados a cabo."
    />
    <Form />
  </div>
</template>

<script>
import Presentation from '../components/Presentation.vue'
import Form from '../components/Contact/Form.vue'

export default {
  name: 'Contact',
  components: {
    Presentation,
    Form
  }
}
</script>