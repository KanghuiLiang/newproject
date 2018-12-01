<template>
  <div id="app">
    <v-app light>
    <div id="nav">
      <Nav/>
    </div>
    <router-view/>
    <Footer />
    </v-app>
  </div>
</template>

<script lang="ts">
    import Footer from '@/components/Footer.vue';
    import Nav from './components/Nav.vue';
    export default {
        name: 'app',
        components: {
            Footer,
            Nav
        }
    }
</script>
<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  font-size 20px
  text-align center
  color gray

#nav
  padding 30px
  a
    font-weight bold
    color gray
    &.router-link-exact-active
      color #42b983
</style>
