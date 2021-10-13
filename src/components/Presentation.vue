<template>
    <v-row class="row">
        <v-container>
            <v-col cols="7" class="py-16">
                <h1 class="playball mb-2">{{ title }}</h1>
                <p>{{ subtitle }}</p>
            </v-col>
        </v-container>
    </v-row>
</template>

<script>
export default {
    name: 'Presentation',
    props: {
        title: String,
        subtitle: String
    }
}
</script>

<style scoped>
h1
{
    font-size: 3.25rem;
    font-weight: 500;
}

p
{
    font-weight: 300;
}

.row
{
    background-color: #000;
    color: #FFF;
}
</style>