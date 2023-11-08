<template>
    <v-app>
        <BroadcastView />
        <v-main>
            <router-view />
        </v-main>

    </v-app>
</template>

<script>

import BroadcastView from "@/components/BroadcastView.vue";

export default {
    name: 'App',

    components: {
        BroadcastView
    },

    data: () => ({
        //
    }),
}
</script>
