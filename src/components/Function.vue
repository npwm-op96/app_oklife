<template>
  <v-row>
    <v-col class="d-flex justify-center">
      <v-col cols="6">
        <v-row>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #F9A825;"  width="250" height="250px" src="https://soleraam.com/wp-content/uploads/2018/08/What-Is-Investment-Protection-and-Why-Do-You-Need-It.jpeg"></v-img>
            </v-card>
            <h1>Protection</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img width="250" style="border: 20px solid #F06292;" height="250px" src="https://www.canarahsbclife.com/content/dam/choice/blog-inner/images/a-health-insurance-policy-to-protect-you-from-health-and-financial-risks.jpg"></v-img>
            </v-card>
            <h1>Health</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #0288D1;" width="250" height="250px" src="https://static8.depositphotos.com/1029150/869/i/600/depositphotos_8692025-stock-photo-education.jpg"></v-img>
            </v-card>
            <h1>Education</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #546E7A;" width="250" height="250px" src="https://www.lpl.com/content/dam/lpl-www/images/Article_Page/ARTICLE-calculator-image-680x500.jpg"></v-img>
            </v-card>
            <h1>Tax</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #FF9E80;" width="250" height="250px" src="https://ggsc.s3.amazonaws.com/images/uploads/Seven_Ways_to_Find_Your_Purpose_in_Life.jpg"></v-img>
            </v-card>
            <h1>Life</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #A7FFEB;"  width="250" height="250px" src="https://iadsb.tmgrup.com.tr/8801f1/1200/627/0/10/1000/532?u=https://idsb.tmgrup.com.tr/2020/01/14/1579004252799.jpg"></v-img>
            </v-card>
            <h1>Investment</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #BCAAA4;"  width="250" height="250px" src="https://www.dmc.tv/images/articles/dhamma.com/620123.4.jpg"></v-img>
            </v-card>
            <h1>Heritage</h1>
            <h1>Planning</h1>
          </v-col>
          <v-col cols="6" class="">
            <v-card class="rounded-card mb-10" width="250px" height="250px">
              <v-img style="border: 20px solid #AED581;"  width="250" height="250px" src="data:image/jpeg;base64,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"></v-img>
            </v-card>
            <h1>Retirement</h1>
            <h1>Planning</h1>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="6"> </v-col>
    </v-col>
  </v-row>
</template>
<style>
.rounded-card {
 
  margin-left: auto;
  margin-right: auto;
  border-radius: 50% !important;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25) !important;
}
</style>