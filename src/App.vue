<template>
  <v-app>
  <v-card
    color="grey lighten-4"
    flat
    height="60px"
    tile
    app
  >
    <v-toolbar
    >
      <div class="pl-5 d-flex align-center">
        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="120"
          src="./components/Picture1.png"
          width="150"
        />
      </div>

      <v-spacer></v-spacer>

     <div class="pl-5 d-flex align-center">
        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="120"
          src="./components/Picture2.png"
          width="150"
        />
      </div>
    </v-toolbar>
  </v-card>

    <v-main class="" height="100vh">
      <login />
    </v-main>
  </v-app>
</template>

<script>
import login from './components/login/login.vue'

export default {
  name: 'App',
  components:{
    login,
  }
};
</script>