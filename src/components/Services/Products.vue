<template>
    <v-container>
        <h2 class="mb-12">¿Cómo Podemos Ayudarte?</h2>
        <v-row class="mb-10">
            <v-col>
                <img src="../../assets/1.jpg" alt="Alto relieve" height="250">
                <p>Alto relieve</p>
            </v-col>
            <v-col>
                <img src="../../assets/1.jpg" alt="Facturas autorizadas por el SENIAT" height="250">
                <p>Facturas autorizadas por el SENIAT</p>
            </v-col>
            <v-col>
                <img src="../../assets/1.jpg" alt="Alto relieve" height="250">
                <p>Tarjetas de boda, bautizo y Bar Mitzvah</p>
            </v-col>
        </v-row>
        <v-row>
            <v-col>
                <img src="../../assets/1.jpg" alt="Etiquetas" height="250">
                <p>Etiquetas</p>
            </v-col>
            <v-col>
                <img src="../../assets/1.jpg" alt="Facturas" height="250">
                <p>Facturas</p>
            </v-col>
            <v-col>
                <img src="../../assets/1.jpg" alt="Estampación" height="250">
                <p>Estampación</p>
            </v-col>
        </v-row>
        <v-row class="justify-center">
            <v-btn class="py-6 mt-10 mb-16" color="#EFB810" to="/contact">Solicita un Presupuesto<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name: 'Products'
}
</script>

<style scoped>
h2
{
    font-size: 1.75em;
    font-weight: 700;
}

p
{
    margin-top: 20px;
    font-weight: 600;
    font-size: 1.1em;
}
</style>