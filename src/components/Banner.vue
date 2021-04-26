<template>
  <v-col class="d-flex justify-center main-banner banner-color">
      <v-col class="d-flex">
        <v-col class="text-left white--text" cols="6">
          <v-col
            ><div class="main-font">
            <p class="ml-5">มั่งคั่งและมั่นคง</p>

               <p class="ml-15 mt-n10">Wealth & Wellness</p>
            </div>
          </v-col>
        </v-col>
        <v-col cols="2" class="align-self-center">
          <v-layout align-center justify-center>
            <v-flex>
              <v-btn rounded large class="btn-register pt-8 pb-8 pl-15 pr-15"
                ><b><h2>REGISTER</h2></b></v-btn
              >
            </v-flex>
          </v-layout>
        </v-col>
        <v-col cols="4" class="align-self-center">
          <v-layout align-center justify-center>
            <v-flex>
              <h1 class="white--text ml-15">CURRENT MEMBER</h1>
            <h1 class="white--text"><v-btn fab ><v-icon>mdi-24px mdi-account-multiple</v-icon></v-btn>   9,000,000</h1>
     
            </v-flex>
          </v-layout>
        </v-col>
      </v-col>
  </v-col>
</template>
<script>
export default {
  name: "Banner",
  data() {
    return {};
  },
};
</script>
<style >
.main-banner {
  position: absolute;
  top: 10px;
  left:0;
  z-index: 1;
}
.main-font{
  padding-left: 14%;
  font-size: 4.5rem;
}

.btn-register {
  background: #393939;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 50px;
  background: #393939 !important;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 50px;
  font-size: larger;
  color: white !important;
}
.banner-color {

  background: linear-gradient(
    91.04deg,
    rgba(113, 248, 215, 0.8) 0%,
    rgba(113, 248, 215, 0.8) 25.27%,
    rgba(35, 183, 243, 0.8) 46.94%
  );

  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
</style>