<template>
  <v-app>
    <app-header />

    <v-main>
      <v-container> Hello World </v-container>
    </v-main>
  </v-app>
</template>

<script>
import AppHeader from '@/components/AppHeader';

export default {
  name: 'App',
  components: {
    AppHeader
  }
};
</script>

<style></style>
