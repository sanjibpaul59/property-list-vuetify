<template>
  <v-container fluid class="grey lighten-2">
    <v-row class="mt-4 justify-center">
      <v-col cols="12" lg="2">
        <v-sheet class="grey lighten-4" min-height="102vh">
          <v-card class="dark" min-height="10vh">
            <v-row class="justify-enter">
              <v-col cols="12" lg="6" class="mt-6 ml-2">
                <h4 text plain large class="amber--text text-capitalize ml-2">
                  Filters
                </h4>
                <h4 class="ml-2 font-weight-bold">___</h4>
              </v-col>
              <v-col cols="12" lg="5" class="mt-4">
                <v-btn text large class="text-capitalize ml-2">Reset All</v-btn>
              </v-col>
            </v-row>
          </v-card>
        </v-sheet>
      </v-col>
      <v-col cols="12" lg="9">
        <!-- <v-sheet class="grey lighten-4 mb-5" min-height="10vh">
          
        </v-sheet> -->
        <v-card class="grey lighten-4 mb-5" flat min-height="10vh">
          <v-row class="justify-center">
            <v-col cols="12" lg="2" class="mt-4">
              <v-btn
                large
                text
                plain
                class="grey--text text--darken-1 text-capitalize ml-2"
                >All <v-icon right>mdi-chevron-down</v-icon></v-btn
              >
            </v-col>
            <v-divider light vertical inset></v-divider>
            <v-col cols="12" lg="3" class="mt-4">
              <v-btn
                large
                text
                plain
                class="grey--text text--darken-1  text-capitalize"
                ><v-icon left>mdi-google-maps</v-icon> Location</v-btn
              >
            </v-col>
            <v-divider light vertical inset></v-divider>
            <v-col cols="12" lg="3" class="mt-4">
              <v-btn
                large
                text
                plain
                class="grey--text text--darken-1  text-capitalize"
              >
                <v-icon left>mdi-home-modern</v-icon> Property Type</v-btn
              >
            </v-col>
            <v-divider light vertical inset></v-divider>
            <v-col cols="12" lg="4" class="mt-4">
              <v-btn
                large
                text
                plain
                class="grey--text text--darken-1 text-capitalize"
              >
                <v-icon left>mdi-cash-multiple</v-icon> Budget</v-btn
              >
            </v-col>
          </v-row>
        </v-card>
        <v-sheet class="grey lighten-4" min-height="90vh"></v-sheet>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
