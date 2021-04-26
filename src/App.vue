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

@font-face {
  font-family: "Proxima Nova Bold";
  src: url(/font/);
}
#app {
  font-family: "FC Minimal Regular";
  src: url(/font/FC-Minimal/FCMinimalRegular.otf);


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
