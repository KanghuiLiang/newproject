<tmplate>
<v-app id="inspire">
    <v-container grid-list-md text-xs-center>
        <v-layout row wrap>
            <v-flex v-for="i in 4" :key="`3${i}`" xs3>
                <v-card dark color="secondary">
                    <v-card-text class="px-0">{{ msg }}</v-card-text>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</v-app>
</tmplate>

<script lang="'ts">
    import { Component, Prop, Vue} from "vue-property-decorator";

    @Component
    export default class Grid extends Vue {
        @Prop() private msg!:string;
    }

</script>
