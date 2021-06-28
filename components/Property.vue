<template>
  <div>
    <v-row no-gutters>
      <v-col cols="3">
        <v-card>
          <v-img
            height="300px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          ></v-img>
        </v-card>
      </v-col>
      <v-col cols="8" class="mt-8">
        <v-sheet class="grey lighten-3">
          <v-card class="grey lighten-3 black--text">
            <v-row>
              <v-col cols="8">
                <v-card-title primary-title>
                  Property Name
                </v-card-title>
                <v-card-subtitle class="black--text">
                  By Owner Name
                </v-card-subtitle>
                <v-card-text>
                  1234 Beach Street, London Market Value: BDT 55,000,000 Status:
                  <span class="red--text">Fully Rented</span>
                  <v-icon>iconName</v-icon>
                </v-card-text>
              </v-col>
              <v-col cols="4"> </v-col>
            </v-row>
          </v-card>
        </v-sheet>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
