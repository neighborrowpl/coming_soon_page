<template>
  <v-app>
    <v-content>
      <v-container
        fluid
        class="fill-height pa-0 ma-0 justify-end"
      >
        <v-row class="fill-height">
          <v-col
            cols="12" md="4"
            class="d-flex align-center mx-auto"
          >
            <TextLeft/>
          </v-col>
          <v-col
            md="8"
            id="right-image"
            class="d-none d-md-flex"
          >
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import TextLeft from './components/TextLeft.vue';

export default {
  name: 'App',

  components: {
    TextLeft,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
  #right-image {
    background-image: url('./assets/apartments.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: left bottom;
  }
</style>
