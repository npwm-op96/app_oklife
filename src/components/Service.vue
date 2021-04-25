<template>
  <div class="row">
    <v-col class="d-flex justify-center">
      <v-hover v-slot="{ hover }" open-delay="200">
        <v-card
          :elevation="hover ? 16 : 2"
          :class="{ 'on-hover': hover }"
          height="600"
          width="500"
        >
          <v-img class="white--text" height="600px" src="/image/service/as.jpg">
            <v-card-title class="mt-2 ml-2 text-left">
              <v-col cols="8" class="topic-head black--text text-left">
                <h1>ASSURANCE</h1>
              </v-col>
            </v-card-title>
            <v-card-title class="pt-50">
              <v-col cols="12" class="text-center">
                <v-btn rounded class="btn-more white--text" large
                  ><h2>MORE</h2></v-btn
                >
              </v-col>
            </v-card-title>
          </v-img>
        </v-card>
      </v-hover>
    </v-col>
    <v-col class="d-flex justify-center">
      <v-hover v-slot="{ hover }" open-delay="200">
        <v-card
          :elevation="hover ? 16 : 2"
          :class="{ 'on-hover': hover }"
          height="600"
          width="500"
        >
          <v-img class="white--text" height="600px" src="/image/service/in.jpg">
            <v-card-title class="mt-2 ml-2 text-left">
              <v-col cols="8" class="topic-head black--text text-left">
                <h1>INSURANCE</h1>
              </v-col>
            </v-card-title>
            <v-card-title class="pt-50">
              <v-col cols="12" class="text-center">
                <v-btn rounded class="btn-more white--text" large
                  ><h2>MORE</h2></v-btn
                >
              </v-col>
            </v-card-title>
          </v-img>
        </v-card>
      </v-hover>
    </v-col>
    <v-col class="d-flex justify-center">
      <v-hover v-slot="{ hover }" open-delay="200">
        <v-card
          :elevation="hover ? 16 : 2"
          :class="{ 'on-hover': hover }"
          height="600"
          width="500"
        >
          <v-img
            class="white--text"
            height="600px"
            src="/image/service/p_a.jpeg"
          >
            <v-card-title class="mt-2 ml-2 text-left">
              <v-col cols="8" class="topic-head black--text text-left">
                <h1>ASSETS</h1>
              </v-col>
            </v-card-title>
            <v-card-title class="pt-50">
              <v-col cols="12" class="text-center">
                <v-btn rounded class="btn-more white--text" large
                  ><h2>MORE</h2></v-btn
                >
              </v-col>
            </v-card-title>
          </v-img>
        </v-card>
      </v-hover>
    </v-col>
  </div>
</template>
<script>
export default {
  name: "Service",
  data: () => {
    return {};
  },
};
</script>
<style >
.btn-more {
  background: linear-gradient(135deg, #90f7ec 0%, #32ccbc 100%);
  width: 200px;
  height: 200px;
  padding: 30px !important;
}
.topic-head {
  background-color: white;
  width: auto;
}
.pt-50 {
  padding-top: 350px !important;
}
</style>
<style lang="sass" scoped>
.v-card.on-hover.theme--dark
  background-color: rgba(#FFF, 0.8)
  >.v-card__text
    color: #000
</style>