<template>
  <v-row>
    <v-img
      :min-height="'calc(100vh - ' + $vuetify.application.top + 'px)'"
      src="@/assets/parallax.jpg"
    >
      <v-theme-provider dark>
        <v-container fill-height>
          <v-row align="center" class="white--text mx-auto" justify="center">
            <v-col class="white--text text-center" cols="12" tag="h1"> </v-col>

            <v-btn class="align-self-end" fab outlined>
              <v-icon>mdi-chevron-double-down</v-icon>
            </v-btn>
          </v-row>
        </v-container>
      </v-theme-provider>
    </v-img>
  </v-row>
</template>

<script>
export default {
  name: "Hero",
};
</script>
