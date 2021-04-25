<template>
  <v-app>
   <Navbar/>
    <v-main>
      <Layout />
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>
import Layout from "./components/Layout";
import Footer from "./components/Footer";
import Navbar from "./components/Navbar";



export default {
  name: "App",

  components: {
    Layout,
    Footer,
    Navbar
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
