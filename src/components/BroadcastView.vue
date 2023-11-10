<template>
    <v-layout>

        <v-navigation-drawer
            class="bg-grey-darken-4"
            width="300"
        >
            <v-list>
                <v-list-item>

                    <v-btn
                        color="grey-darken-4"
                        class="d-flex flex-row align-center justify-start"
                        width="300"
                        height="48"
                    >

                        <v-icon
                            icon="mdi-account"
                            size="42"
                            color="#E7CFB8"
                            class="mr-3"
                        >
                        </v-icon>

                        <span class="text-white text-subtitle-1">account name</span>

                    </v-btn>

                </v-list-item>
            </v-list>
        </v-navigation-drawer>
        <v-app-bar
            :elevation="0"
            class="bg-grey-darken-4"
            height="49"
        >
            <template v-slot:prepend>
                <v-btn
                    icon="mdi-arrow-left"
                    color="#E7CFB8"
                    size="40"
                ></v-btn>
            </template>

            <span class="text-white text-subtitle-1 ml-2">broadcast name</span>

            <template v-slot:append>
                <v-btn
                    right
                    icon="mdi-theme-light-dark"
                    color="#E7CFB8"
                    size="40"
                    class="mr-1"
                ></v-btn>

                <v-btn
                    icon="mdi-cog"
                    color="#E7CFB8"
                    size="40"
                    class="mr-1"
                ></v-btn>

                <v-btn
                    icon="mdi-page-layout-sidebar-left"
                    color="#E7CFB8"
                    size="40"
                ></v-btn>
            </template>
        </v-app-bar>

        <v-main
            class="d-flex align-center flex-column justify-end bg-grey-darken-3"
            style="min-height: 100vh;"
        >
            <span class='text-h6 text-uppercase font-weight-light'>the broadcast will start soon...</span>
            <div class="d-flex align-center flex-column justify-end">
                <div class="d-flex justify-center">
                    <v-btn
                        icon="mdi-chevron-down"
                        color="#E7CFB8"
                        size="36"
                        variant="plain"
                    ></v-btn>
                </div>
                <div class="mt-1 mb-5">
                    <v-btn
                        variant="tonal"
                        icon="mdi-video"
                        color="#E7CFB8"
                        size="48"
                    ></v-btn>
                    <v-btn
                        class="mx-2"
                        variant="tonal"
                        icon="mdi-text-box"
                        color="#E7CFB8"
                        size="48"
                    ></v-btn>
                    <v-btn
                        variant="tonal"
                        icon="mdi-microphone"
                        color="#E7CFB8"
                        size="48"
                    ></v-btn>
                </div>
            </div>
        </v-main>
    </v-layout>
</template>

<script>

export default {

}
</script>
