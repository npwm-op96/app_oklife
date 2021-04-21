<template>

  <v-app >
    <v-app-bar
      height="80"
      app
      flat
      color="white"
      light
      
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink "
          contain
          src="../image/logo.png" 
          transition="scale-transition"
          width="60"
        />
        <span>OK ไลฟ์</span>

      </div>

      <v-spacer></v-spacer>

        <span class="mr-5">HOME</span>
        <span class="mr-5">ABOUNT</span>
        <span class="mr-5">CONTACT</span>

              <span><v-icon>mdi-account</v-icon></span>

        <span class="ml-5 mr-3">Login</span>
    </v-app-bar>

    <v-main>
      <Layout/>
    </v-main>
  </v-app>
</template>

<script>
import Layout from './components/Layout';

export default {
  name: 'App',

  components: {
    Layout,
  },

  data: () => ({
    //
  }),
};
</script>
<style >
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif; /* this was it */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
