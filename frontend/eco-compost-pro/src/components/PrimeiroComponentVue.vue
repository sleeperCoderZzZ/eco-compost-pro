<template>
    <div>
        <v-container class="fill-height">
            <v-row justify="center" align="center">
                <v-col cols="auto">
                    <v-card width="550px" class="d-flex flex-column" color="teal-darken-4" variant="elevated"
                        rounded="50%">
                        <v-row align="center" justify="center">
                            <v-col cols="12" sm="6" md="4" lg="4">
                                <v-card-item>
                                            <v-card-title class="text-center text-orange-darken-4">
                                                <h1>
                                                    TITULO
                                                </h1>
                                            </v-card-title>
                                </v-card-item>
                            </v-col>
                        </v-row>
                        <v-row align="center" justify="center">
                            <v-col cols="12" sm="6" md="4" lg="8">
                                <v-card-item>
                                            <v-form>
                                                <v-row align="center" justify="center">
                                                    <v-col cols="12">
                                                        <v-text-field
                                                            label="Nome do usuário"
                                                            variant="filled"
                                                            color="primary"
                                                            class="ma-0"
                                                            dense
                                                        >

                                                        </v-text-field>
                                                    </v-col>
                                                </v-row>
                                                <v-row align="center" justify="center">
                                                    <v-col cols="12">
                                                        <v-text-field
                                                            label="Email"
                                                            variant="filled"
                                                            color="primary"
                                                            class="ma-0"
                                                            dense
                                                        >

                                                        </v-text-field>
                                                    </v-col>
                                                </v-row>
                                                <v-row align="center" justify="center">
                                                    <v-col cols="12">
                                                        <v-text-field
                                                            label="Senha"
                                                            variant="filled"
                                                            color="primary"
                                                            class="ma-0"
                                                            dense
                                                        >

                                                        </v-text-field>
                                                    </v-col>
                                                </v-row>
                                            </v-form>
                                </v-card-item>
                            </v-col>
                        </v-row>
                        <v-row align="center" justify="center">
                            <v-col cols="12" sm="6" md="4" lg="4">
                                <v-card-item class="ma-0">
                                            <v-card-actions>
                                                <v-btn style="max-width: 100%; width: 100%;"
                                                variant="tonal"
                                                >
                                                    botão
                                                </v-btn>
                                            </v-card-actions>
                                </v-card-item>
                            </v-col>
                        </v-row>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>