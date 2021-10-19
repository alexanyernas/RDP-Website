<template>
    <v-row class="row mb-16 pt-6">
        <v-col class="px-16 my-auto">
            <h1 class="playball mb-10">Presencia de la excelencia en la impresión...!</h1>
            <v-btn class="py-6" color="#EFB810" to="/about">Conoce sobre nosotros<v-icon class="ml-3">mdi-arrow-right</v-icon></v-btn>
        </v-col>
        <v-col>
            <img src="../../assets/8.jpg" alt="HeroImage" height="600">
        </v-col>
    </v-row>
</template>

<script>
export default {
    name: 'HeroImage'
}
</script>

<style scoped>
.row
{
    color: #FFF;
    background-color: #000;
}

h1
{
    font-weight: 500;
    font-size: 3.75rem;
}
</style>