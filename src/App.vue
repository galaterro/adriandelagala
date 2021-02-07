<template>
<v-app>
  <v-navigation-drawer app v-model="drawer" temporary>
    <!-- -->
  </v-navigation-drawer>

  <v-app-bar app color="primary">
    <v-app-bar-nav-icon @click.stop="drawer = !drawer" dark></v-app-bar-nav-icon>
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer app>
    <!-- -->
  </v-footer>
</v-app>
</template>

<script>

export default {
  name: 'App',

  components: {

  },

  data: () => ({
drawer: null
  }),
};
</script>
