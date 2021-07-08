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
    <filter-content />
  </v-sheet>
</template>

<script>
import FilterContent from "./FilterContent.vue"
export default {
  components: { FilterContent },
}
</script>

<style lang="scss" scoped></style>
