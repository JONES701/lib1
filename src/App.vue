<style>
@import url('@/assets/styles.css');
</style>


<template>
  <v-app>
    <v-app-bar
      app
      color="secondary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://media.istockphoto.com/id/826736292/vector/librarian-woman-with-books-flat-vector-illustration.jpg?s=612x612&w=0&k=20&c=-RqOIuH29W9bT2NbzYbcSXrKBfLcE1IaZ2cHiLxkS1Y="
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://www.shutterstock.com/image-vector/librarian-word-concept-colorful-on-260nw-1292527018.jpg"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="#"
        target="_blank"
        text
      >
        <span class="mr-2">Login</span>
        <v-icon>mdi-open-in-new</v-icon>
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
