<template>
  <v-container class="mt-16 mb-16">
      <v-row>
        <v-col class="my-auto col-blue">
            <div>
                <h3>¿Tienes una idea en mente?</h3>
                <h2>Coméntanos qué te gustaría realizar</h2>
                <p>Comunícate con nosotros indicándonos qué te gustaría realizar y así poder ofrecerte un presupuesto para desarrollar tus ideas.</p>
            </div>
        </v-col>
        <v-col>
            <v-form
                ref="form"
                lazy-validation
                @submit.prevent=""
            >
                <v-row>
                    <v-col cols="6">
                        <v-text-field
                            v-model="information.name"
                            label="Nombre"
                            solo
                            required
                        ></v-text-field>
                    </v-col>

                    <v-col cols="6">
                        <v-text-field
                            v-model="information.lastname"
                            label="Apellido"
                            solo
                            required
                        ></v-text-field>
                    </v-col>
                </v-row>

                <v-text-field
                    v-model="information.phone"
                    label="Número telefónico"
                    solo
                    required
                ></v-text-field>

                <v-text-field
                    v-model="information.email"
                    label="Correo electrónico"
                    solo
                    required
                ></v-text-field>

                <v-textarea
                    v-model="information.message"
                    label="Mensaje o comentario"
                    name="name"
                    solo
                ></v-textarea>

                <v-btn
                    color="#EFB810"
                    class="mr-4 py-6"
                    type="submit"
                >
                    Enviar mensaje
                </v-btn>
            </v-form> 
        </v-col>
      </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'Form',
    data () {
        return {
            information: {
                name: '',
                lastname: '',
                phone: '',
                email: '',
                message: ''
            }
        }
    }
}
</script>

<style scoped>
.col-blue
{
    background-color: #133369;
    color: #FFF;
}
</style>