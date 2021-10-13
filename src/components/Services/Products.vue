<template>
    <v-container class="mt-16">
        <h2>¿Cómo Podemos Ayudarte?</h2>
        <v-col 
            v-for="(product, index) in products" 
            :key="index"
            cols="4"
        >
            <img :src="product.img" :alt="product.title">
            <p>{{ product.title }}</p>
        </v-col>
    </v-container>
</template>

<script>
export default {
    name: 'Products',
    data () {
        return {
            products: [
                {
                    title: 'Alto relieve',
                    img: '../../assets/1.jpg'
                },
                {
                    title: 'Facturas autorizadas por el SENIAT',
                    img: '../../assets/1.jpg'
                },
                {
                    title: 'Tarjetas de boda, bautizo y Bar Mitzvah',
                    img: '../../assets/1.jpg'
                },
                {
                    title: 'Etiquetas',
                    img: '../../assets/1.jpg'
                },
                {
                    title: 'Facturas',
                    img: '../../assets/1.jpg'
                },
                {
                    title: 'Estampación',
                    img: '../../assets/1.jpg'
                }
            ]
        }
    }
}
</script>