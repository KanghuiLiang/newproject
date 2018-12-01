<template>
    <div class="footer">
        <v-footer
                dark
                height="auto"
        >
            <v-card
                    class="flex"
                    flat
                    tile
            >
                <v-card-title class="teal">
                    <strong class="subheading">Get connected with ME on social networks!</strong>
                </v-card-title>
                <v-btn
                            v-for="icon in icons"
                            :key="icon"
                            class="mx-3"
                            dark
                            icon
                    >
                        <v-icon size="24px">{{ icon }}</v-icon>
                    </v-btn>


                <v-card-actions class="grey darken-3 justify-center">
                    &copy;2018 — <strong>HUIHUIHUI</strong>
                </v-card-actions>
            </v-card>
        </v-footer>
    </div>
</template>

<script>
    export default {
        name: 'Footer',
        data: () => ({
            icons: [
                'fab fa-facebook',
                'fab fa-twitter',
                'fab fa-google-plus',
                'fab fa-linkedin',
                'fab fa-instagram'
            ]
        })
    }
</script>
<style>
    .footer {
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: lightpink;
        color: white;
        text-align: center;
    }
</style>
