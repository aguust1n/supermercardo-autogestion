<template>
    <v-app-bar color="blue-grey darken-4" dense>
        <router-link to="/" class="hidden-md-and-up">
            <v-img
                src="/img/logoSuper_blanco.svg"
                height="100"
                width="180"
            />
        </router-link>
        <router-link to="/">
            <v-img
                class="mx-2 hidden-sm-and-down"
                src="/img/logoSuper_blanco.svg"
                width="200"
            />
        </router-link>
        <v-icon>mdi-login-variant</v-icon>
    </v-app-bar>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style scoped>

</style>