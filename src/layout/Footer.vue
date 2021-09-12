<template>
    <div>
        <v-footer
                color="blue-grey darken-4">
            <v-row
                    align="center"
                    justify="center"
                    class="ma-2"
                    no-gutters
            >
                <v-col
                        cols="12"
                        align="center"
                ><v-img
                        width="180"
                        alt=""
                        class="hidden-xs-only"
                        src="/img/logoSuper_blanco.svg"
                ></v-img>
                <v-img
                        width="120"
                        alt=""
                        class="hidden-sm-and-up"
                        src="/img/logoSuper_blanco.svg"
                ></v-img>
                </v-col>
            </v-row>
        </v-footer>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>

</style>