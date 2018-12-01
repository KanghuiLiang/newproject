<template>
  <div class="home">
      <v-app id="inspire">
          <div id="home">
              <div class="greeting">
                  <h1>STEM</h1>
                  <h3>Knowledge is Treasure</h3>
                  <div class="scrollArrow">
                      <p class="scrollText"></p>
                  </div>
              </div>

          </div>
      </v-app>
  </div>

</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  components: {

  }
})
export default class Home extends Vue {}
</script>

<style scoped lang="stylus">

</style>
