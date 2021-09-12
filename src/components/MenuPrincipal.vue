<template>
    <div class="Montserrat">
        <v-card color="amber accent-2">
            <v-navigation-drawer
                    permanent
            >
                <v-list color="indigo lighten-4">
                    <v-list-item class="px-2">
                        <v-list-item-avatar>
                            <v-img alt="" :src="'{{foto}}'"></v-img>
                        </v-list-item-avatar>
                    </v-list-item>

                    <v-list-item link>
                        <v-list-item-content>
                            <v-list-item-title class="text-h6">
                                {{name}}
                            </v-list-item-title>
                            <v-list-item-subtitle>{{email}}</v-list-item-subtitle>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>

                <v-divider></v-divider>

                <v-list
                    nav
                    dense
                    color="indigo lighten-4"
                >
                    <v-list-item link>
                        <v-list-item-icon>
                            <v-icon>mdi-home-circle-outline</v-icon>
                        </v-list-item-icon>
                        <v-list-item-title class="font-weight-bold">Home</v-list-item-title>
                    </v-list-item>
                    <v-list-item link>
                        <v-list-item-icon>
                            <v-icon>mdi-folder-edit-outline</v-icon>
                        </v-list-item-icon>
                        <v-list-item-title class="font-weight-bold">Editar</v-list-item-title>
                    </v-list-item>
                    <v-list-item link>
                        <v-list-item-icon>
                            <v-icon>mdi-plus-circle-outline</v-icon>
                        </v-list-item-icon>
                        <v-list-item-title class="font-weight-bold">Agregar</v-list-item-title>
                    </v-list-item>
                </v-list>
            </v-navigation-drawer>
        </v-card>
    </div>
</template>

<script>
    export default {
        name: "MenuPrincipal",
        props:{
            name: String,
            foto: String,
            email: String,
        }
    }
</script>

<style scoped>

</style>