<template>
  <v-container class="mt-16 mb-16">
      <v-row class="form-row">
        <v-col class="col-blue px-16">
            <div>
                <h4 class="mb-4">¿Tienes una idea en mente?</h4>
                <h2 class="mb-4">Coméntanos qué te gustaría realizar</h2>
                <p>Comunícate con nosotros indicándonos qué te gustaría realizar y así poder ofrecerte un presupuesto para desarrollar tus ideas.</p>
            </div>
        </v-col>
        <v-col class="py-10 px-16">
            <h2 class="mb-3">Llena nuestro formulario</h2>
            <v-form
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

.form-row
{
    box-shadow: 15px 20px 90px #DDD;
}

.col-blue div
{
    margin-top: 35%;
}

.col-blue h2
{
    font-size: 36px;
    line-height: 1.2;
}

.col-blue h4
{
    font-weight: 500;   
}

.col-blue p
{
    color: #CCC;
}
</style>