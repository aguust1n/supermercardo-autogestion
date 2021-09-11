<template>
    <div>
        <v-footer
                color="blue-grey darken-4">
            <v-row
                    align="center"
                    justify="center"
                    class="ma-2"
            >
                <v-col
                        cols="6"
                        md="6"
                        align="center"
                ><v-img
                        width="180"
                        class="hidden-xs-only"
                        src="/img/"
                ></v-img>
                    <v-img
                            width="150"
                            class="hidden-sm-and-up"
                            src="/img/"
                    ></v-img>
                </v-col>
                <v-col
                        cols="6"
                        md="6"
                        align="center"
                >
                    <v-img
                            width="180"
                            class="hidden-xs-only"
                            src="/img/"
                    ></v-img>
                    <v-img
                            width="140"
                            class="hidden-sm-and-up"
                            src="/img/"
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