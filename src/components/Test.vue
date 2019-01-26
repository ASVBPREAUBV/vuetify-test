<template>
    <v-layout align-space-between justify-space-around row fill-height>

    <v-progress-circular :value="20"></v-progress-circular>

    <v-progress-circular :value="40"></v-progress-circular>

    <v-progress-circular :value="60"></v-progress-circular>

    <v-progress-circular :value="80"></v-progress-circular>

    <v-progress-circular :value="100"></v-progress-circular>
    </v-layout>

</template>

<script>
    export default {
        data: () => ({
            ecosystem: [
                {
                    text: 'vuetify-loader',
                    href: 'https://github.com/vuetifyjs/vuetify-loader'
                },
                {
                    text: 'github',
                    href: 'https://github.com/vuetifyjs/vuetify'
                },
                {
                    text: 'awesome-vuetify',
                    href: 'https://github.com/vuetifyjs/awesome-vuetify'
                }
            ],
            importantLinks: [
                {
                    text: 'Documentation',
                    href: 'https://vuetifyjs.com'
                },
                {
                    text: 'Chat',
                    href: 'https://community.vuetifyjs.com'
                },
                {
                    text: 'Made with Vuetify',
                    href: 'https://madewithvuetifyjs.com'
                },
                {
                    text: 'Twitter',
                    href: 'https://twitter.com/vuetifyjs'
                },
                {
                    text: 'Articles',
                    href: 'https://medium.com/vuetify'
                }
            ],
            whatsNext: [
                {
                    text: 'Explore components',
                    href: 'https://vuetifyjs.com/components/api-explorer'
                },
                {
                    text: 'Select a layout',
                    href: 'https://vuetifyjs.com/layout/pre-defined'
                },
                {
                    text: 'Frequently Asked Questions',
                    href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions'
                }

            ]
        })
    }
</script>

<style>

</style>
