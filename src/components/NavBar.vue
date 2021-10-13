<template>
    <v-app-bar
        app
        color="#000"
        dark
        elevate-on-scroll
        elevation="6"
        class="px-16"
    >
        <v-toolbar-title>
            Relieves Del Pozo
        </v-toolbar-title>

        <v-spacer></v-spacer>
        
        <v-btn 
            v-for="(link, index) in links" 
            :key="index" 
            :to="link.to"
            text
            class="mr-2"
        >
            {{ link.text }}
        </v-btn>
        
        <v-spacer></v-spacer>

        <div class="mt-3">
            <p>Comunícate con nosotros<br>Llama: +58 212 238 4094</p>
        </div>

    </v-app-bar>
</template>

<script>
export default {
    name: 'NavBar',
    data () {
        return {
            links: [
                {
                    text: 'Inicio',
                    to: '/'
                },
                {
                    text: 'Nosotros',
                    to: '/about'
                },
                {
                    text: 'Servicios',
                    to: '/services'
                },
                {
                    text: 'Contacto',
                    to: '/contact'
                }
            ]
        }
    }
}
</script>