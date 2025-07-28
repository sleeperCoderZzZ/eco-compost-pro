<template>
    <v-sheet color="blue-grey-darken-4" :width="'35vw'" :elevation="24" class="pa-4 rounded-lg mx-auto">
        <v-container>
            <v-row justify="center">
                <v-col cols="12" md="8">
                    <h1 class="text-center text-h3 text-grey-lighten-4">Login</h1>
                </v-col>
            </v-row>
        </v-container>

        <v-form>
            <v-container>
                <v-row justify="center">
                    <v-col cols="12" md="8">
                        <v-text-field
                            label="Login"
                            variant="solo"
                            rounded
                            bg-color="blue-grey-darken-1"
                            full-width>

                        </v-text-field>
                    </v-col>
                </v-row>
                <v-row justify="center">
                    <v-col cols="12" md="8">
                        <v-text-field
                            label="Senha"
                            variant="solo"
                            type="password"
                            rounded
                            bg-color="blue-grey-darken-1"
                            full-width
                            gap="2">
                        </v-text-field>
                    </v-col>
                </v-row>
                <v-row justify="center">
                    <v-col cols="12" md="8">
                        <v-btn
                            color="blue-grey-darken-3"
                            class="mt-4"
                            block
                            gap="5">
                            Entrar
                        </v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </v-form>
    </v-sheet>
</template>
