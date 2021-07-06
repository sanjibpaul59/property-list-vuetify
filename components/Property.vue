<template>
  <div class="d-flex flex-row my-6">
    <v-img
      class="rounded"
      max-height="280px"
      max-width="340px"
      style="flex-basis: 125px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    ></v-img>
    <v-card
      class="rounded-lg mt-4 ml-n4"
      height="210px"
      min-width="714px"
      width="1050px"
      style="backgroundColor:#FCFBFC;"
    >
      <v-row justify="space-around">
        <v-col cols="7" class="ml-4">
          <!-- <v-sheet class="grey lighten-3" style="flex-basis: 125px">
            <v-card class="grey lighten-3 black--text">
              <v-row>
                <v-col cols="8"> -->
          <v-card-title
            primary-title
            class="black--text subtitle-1 font-weight-medium"
          >
            T - 404 Victory Amara Noida Extension
          </v-card-title>
          <v-card-subtitle class="ml-3">
            <v-row>
              <p class="black--text subtitle-2 font-weight-medium">
                By DC Homes Pvt Ltd.
              </p>
            </v-row>
            <v-row>
              <p class="black--text caption mt-n3">
                1234 Beach Street, London
              </p>
            </v-row>
          </v-card-subtitle>

          <v-card-text class="mt-n4">
            <v-row class="d-flex flex-no-wrap">
              <v-col>
                <div class="black--text mb-2">
                  <span class="subtitle-2"> Market Value: </span>&nbsp; &nbsp;
                  &nbsp;
                  <span class="subtitle-2 font-weight-bold"
                    >BDT 55,000,000</span
                  >
                </div>
                <div class="black--text">
                  Status: &nbsp; &nbsp;
                  <span class="pink--text text--darken-1">Fully Rented</span>
                </div>
              </v-col>
            </v-row>
            <v-row class="mt-n2">
              <v-col cols="3" class="black--text">
                <v-icon left color="grey darken-2">mdi-bed</v-icon>
                <span class="font-weight-bold grey--text text--darken-2 "
                  >Bed</span
                >
              </v-col>
              <v-col cols="3" class="black--text">
                <v-icon left color="grey darken-2">mdi-shower</v-icon>

                <span class="font-weight-bold grey--text text--darken-2"
                  >Bath</span
                >
              </v-col>
              <v-col cols="3" class="black--text">
                <v-icon left color="grey darken-2">mdi-garage</v-icon>

                <span class="font-weight-bold grey--text text--darken-2"
                  >Parking</span
                >
              </v-col>
            </v-row>
          </v-card-text>
        </v-col>
        <v-col cols="4" class="black--text">
          <div class="mt-6 d-flex flex-row">
            <div class="ma-2">
              <p class="subtitle-2 ma-0">Token Price</p>
              <p class="title">BDT 100000</p>
              <p class="subtitle-2 blue--text text--darken-2">
                Expected Turn Over
              </p>
            </div>
            <v-divider
              vertical
              light
              class="mx-4 mt-2"
              style="height:70px;"
            ></v-divider>
            <div class="ma-2">
              <p class="subtitle-2 ma-0">Total Tokens</p>
              <p class="title">500</p>
              <p class="subtitle-2 blue--text text--darken-2 font-weight-bold">
                10.05%
              </p>
            </div>
          </div>
          <div class=" mt-n2 text-center">
            <v-btn color="amber" outlined class="black--text rounded-xl "
              ><p class="grey--text text--darken-4 pt-5 font-weight-bold">
                View Details
              </p></v-btn
            >
          </div>
        </v-col>
      </v-row>
      <!-- </v-card>
          </v-sheet> -->
      <!-- </v-col>
      </v-row> -->
    </v-card>
  </div>
</template>

<script>
export default {
  data: () => ({
    absolute: true,
  }),
}
</script>

<style lang="scss" scoped>
$divider-max-height: 1.5rem;
</style>
