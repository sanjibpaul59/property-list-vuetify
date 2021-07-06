<template>
  <v-container fluid class="grey lighten-2">
    <v-row class="mt-4 justify-center">
      <v-col cols="12" lg="2">
        <filter-bar />
      </v-col>
      <v-col cols="12" lg="9">
        <search-card />
        <properties />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import FilterBar from "../components/FilterBar.vue"
import Properties from "../components/Properties.vue"
import SearchCard from "../components/SearchCard.vue"
export default {
  components: { Properties, FilterBar, SearchCard },
}
</script>

<style lang="scss" SearchCardscoped></style>
