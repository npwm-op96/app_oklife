<template>
  <div>
    <v-col>
      <Banner />
    </v-col>
    <Gallary />
    <v-row class="text-center">
      <v-col class="mt-10" cols="12"
        ><span><h1>SERVICE</h1></span>
      </v-col>
      <v-col class=" d-flex justify-center" cols="12">
        <Service />
      </v-col>

      <v-col class="mb-4"> </v-col>

      <v-col class="mb-5" cols="12">
        <v-row justify="center"> <h1>หลักการง่าย ๆ ในการใช้ชีวิต</h1></v-row>
      </v-col>
      <v-col class="mb-5" cols="12">
        <v-row justify="center"> 
        <Function/>
        </v-row>
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
import Service from "./Service";
import Function from "./Function";


export default {
  name: "Layout",
  components: {
    Gallary,
    Banner,
    Service,
    Function
  },
};
</script>
