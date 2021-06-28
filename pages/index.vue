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
        <search-card />
        <properties />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Properties from "../components/Properties.vue"
import SearchCard from "../components/SearchCard.vue"
export default {
  components: { Properties },
}
</script>

<style lang="scss" SearchCardscoped></style>
