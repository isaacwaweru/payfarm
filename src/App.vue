<template>
  <v-app>
    <v-app-bar
      app
      color="#fff"
      dark
      flat
    >
      <div class="d-flex align-center">
        <v-img
            lazy-src="./assets/foot.svg"
             max-height="140"
             max-width="140"
            src="./assets/foot.svg"
          ></v-img>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        color="#53C351"
        height="35"
      >
      Login
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
