<template>
  <v-app>
    <v-app-bar
      absolute
      color="indigo darken-4"
      class="d-flex justify-center text-h4"
      dark
    >
        Lee Kang-Jin 1
    </v-app-bar>
    <v-main>
      <Story/>
    </v-main>
  </v-app>
</template>

<script>
import Story from './components/Story';

export default {
  name: 'App',

  components: {
    Story,
  },

  data: () => ({
    //
  }),
};
</script>
