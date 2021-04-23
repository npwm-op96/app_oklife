<template>
  <div>
  <v-col>
      <Banner/>
  </v-col>

    <Gallary />

    <v-row class="text-center">
    
      <v-col class="mt-10" cols="12"><span><h1>SERVICE</h1></span> </v-col>

      <v-col class="mb-4"> </v-col>

      <v-col class="mb-5" cols="12">
        <v-row justify="center"> </v-row>
      </v-col>

      <v-col class="mb-5" cols="12">
        <v-row justify="center"> </v-row>
      </v-col>

      <v-col class="mb-5" cols="12">
        <v-row justify="center"> </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import Gallary from "./Gallary";
import Banner from "./Banner";

export default {
  name: "Layout",
  components: {
    Gallary,
    Banner
  },
};
</script>
