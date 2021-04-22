<template>
<v-col class="d-flex justify-center main-banner">
<v-card width="95%" height="150px" color="white" class="banner-color">
<v-col cols="4">
<v-row>มั่งคั่งและมั่นคง</v-row>
<v-row>Wealth & Wellness </v-row>

</v-col>
<v-col cols="4" >
    <v-btn class="btn-register" >REGISTER</v-btn>
</v-col>
<v-col cols="4"></v-col>


</v-card>
</v-col>
</template>
<script>
  export default {
      name:"Banner",
    data () {
      return {
       

      }
    },
  }
</script>
<style >
.main-banner{
    position:absolute;
    top: -10px;
    z-index: 1
}
.banner-color{
    background: linear-gradient(91.04deg, rgba(113, 248, 215, 0.8) 0%, rgba(113, 248, 215, 0.8) 25.27%, rgba(35, 183, 243, 0.8) 46.94%);
    opacity: 90%;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.btn-register{
    background: #393939 !important;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 50px;
    font-size: larger;
    color:white !important;
}

</style>