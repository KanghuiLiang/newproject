<template>
<v-app id="inspire">
    <v-container grid-list-xl text-xs-center>
        <v-layout row wrap>
            <v-flex xs10 offset-xs1>
            </v-flex>
            <v-flex xs7 offset-xs5 offset-md2 offset-lg5>
                <v-card dark color="secondary">
                    <v-card-text>ddsds</v-card-text>
                </v-card>
            </v-flex>
            <v-flex xs12 sm5 md3>
                <v-card dark color="primary">
                    <v-card-text>(xs12 | sm5 | md3)</v-card-text>
                </v-card>
            </v-flex>
            <v-flex xs12 sm5 md5 offset-xs0 offset-lg2>
                <v-card dark color="green">
                    <v-card-text>(xs12 | sm5 | md5) offset-(xs0 | lg2)</v-card-text>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</v-app>
</template>

<script lang="ts">
    export default {
        name: 'HomeGrid',
    }
</script>
