<template>
  <v-app>
    <v-app-bar height="80" app flat color="white" light>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink"
          contain
          src="image/logo.png"
          transition="scale-transition"
          width="60"
        />
        <div ><b class="font-navbar head-font">OK ไลฟ์</b></div>
      </div>

      <v-spacer></v-spacer>
            <v-spacer></v-spacer>

      <v-col class="d-flex justify-end font-navbar">
        <v-col> HOME</v-col>
        <v-col> ABOUNT</v-col>
        <v-col> CONTACT</v-col>
        <v-col><b color="blue" class="color-bar">|</b> </v-col>

        <v-col><v-icon>mdi-account</v-icon></v-col>
        <v-col>
          
          Login
        </v-col>
      </v-col>
    </v-app-bar>

    <v-main>
      <Layout />
    </v-main>
  </v-app>
</template>

<script>
import Layout from "./components/Layout";

export default {
  name: "App",

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
  font-family: "Avenir", Helvetica, Arial, sans-serif; /* this was it */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.font-navbar {
  font-size: larger;
}
.color-bar{
  color:"#2196F3";
}
.head-font{
  font-size: 1.8rem;
}
</style>
