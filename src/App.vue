<template>
  <v-app>
    <v-app-bar app color="white" flat>
      <v-toolbar-title>AR-RICE</v-toolbar-title>

      <v-spacer />

      <v-btn plain text small href="#"> Home </v-btn>
      <v-btn plain text small href="#"> About </v-btn>
      <v-btn plain text small href="#"> Customer </v-btn>
      <v-btn plain text small href="#"> Contact Us </v-btn>

      <v-spacer />

      <v-btn plain icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn plain icon>
        <v-icon>mdi-cart-outline</v-icon>
      </v-btn>

      <v-btn plain icon>
        <v-icon>mdi-account-outline</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <v-container> Hello World </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  components: {}
};
</script>

<style></style>
