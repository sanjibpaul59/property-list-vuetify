<template>
  <v-card class="grey lighten-4 mb-5" flat min-height="10vh">
    <v-row class="justify-center">
      <v-col cols="12" lg="2" class="mt-4">
        <CardBtn iconName="mdi-chevron-down" btnName="All" />
      </v-col>
      <v-divider light vertical inset></v-divider>
      <v-col cols="12" lg="3" class="mt-4">
        <CardBtn iconName="mdi-google-maps" btnName="Location" />
      </v-col>
      <v-divider light vertical inset></v-divider>
      <v-col cols="12" lg="3" class="mt-4">
        <CardBtn iconName="mdi-home-modern" btnName="Property Type" />
      </v-col>
      <v-divider light vertical inset></v-divider>
      <v-col cols="12" lg="4" class="mt-4">
        <CardBtn iconName="mdi-cash-multiple" btnName="Budget" />
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    iconName: "mdi-chevron-down",
  }),
}
</script>

<style lang="scss" scoped></style>
