<template>
  <v-app id="inspire">
    <v-app-bar
      app
      color="#5Cb85C"
      flat
    >
      <v-toolbar-title>  ChordSharing  </v-toolbar-title>

      <v-responsive max-width="260">
          <v-text-field
            :elevation="hover ? 24 : 6"
            dense
            flat
            hide-details
            rounded
            solo-inverted
          ></v-text-field>    
      </v-responsive>
      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <v-avatar
        class="hidden-sm-and-down"
        color="grey darken-1 shrink"
        size="32"
      ></v-avatar>
    </v-app-bar>

    <v-main class="grey lighten-3">
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="2"
          >
            <v-sheet
              rounded="lg"
              min-height="268"
            >
              <!--  -->
            </v-sheet>
          </v-col>

          <v-col
            cols="12"
            sm="8"
          >
            <v-sheet
              min-height="70vh"
              rounded="lg"
            >
              <!--  -->
            </v-sheet>
          </v-col>

          <v-col
            cols="12"
            sm="2"
          >
            <v-sheet
              rounded="lg"
              min-height="268"
            >
              <!--  -->
            </v-sheet>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
  export default {
    data: () => ({
      links: [
        'あざらし',
        'Messages',
        'Profile',
        'Updates',
        'あざらしUpdates',
        'あざらしあざらし'
      ],
    }),
  }
</script>