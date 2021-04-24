<template>
    
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
        <v-col> ABOUT</v-col>
        <v-col> CONTACT</v-col>

        <v-col><b color="blue" class="color-bar">|</b> <v-icon>mdi-account-circle</v-icon>Login</v-col>
      </v-col>
    </v-app-bar>

</template>