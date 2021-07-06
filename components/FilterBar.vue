<template>
  <v-sheet class="grey lighten-4 mt-n3">
    <v-card class="dark rounded-0" height="10vh">
      <v-card-title>
        <v-row class="justify-enter">
          <v-col cols="12" lg="6" class="mt-2 ml-2">
            <h5 text plain class="amber--text text-capitalize ml-2">
              Filters
            </h5>
            <v-divider
              inset
              dark
              class="ml-2"
              style="border:1px solid white; width:25px;"
            ></v-divider>
            <!-- <h5 class="ml-2 mt-n4 font-weight-bold">___</h5> -->
          </v-col>
          <v-col cols="12" lg="5" class="mt-2">
            <v-btn text class="text-capitalize ml-2">Reset All</v-btn>
          </v-col>
        </v-row>
      </v-card-title>
    </v-card>
    <v-card class="rounded-0" light height="18vh">
      <v-card-title class="subtitle-1 font-weight-medium">
        Budget
        <v-spacer></v-spacer>
        <v-btn text
          ><v-divider
            inset
            dark
            style="border:1px solid grey; width:25px;"
          ></v-divider
        ></v-btn>
      </v-card-title>
      <v-card-text class="ml-3">
        <v-row>
          <v-col>
            <v-btn
              small
              outlined
              class="rounded-pill text-start"
              color="grey darken-2"
              >value</v-btn
            >
          </v-col>
          <v-col>
            <v-btn small outlined class="rounded-pill" color="grey darken-2"
              >value</v-btn
            >
          </v-col>
        </v-row>
        <v-row>
          <v-col>
            <v-range-slider
              hint="Im a hint"
              max="50"
              min="-50"
              track-color="grey lighten-1"
              color="amber darken-2"
            ></v-range-slider>
          </v-col>
        </v-row>
      </v-card-text>
    </v-card>
  </v-sheet>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
