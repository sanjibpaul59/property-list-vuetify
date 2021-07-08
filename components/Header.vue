<template>
  <v-app-bar app dark flat>
    <v-toolbar-title class="mx-16">
      <span class="amber--text text--darken-2">EST</span>ATE
      Inc.</v-toolbar-title
    >
    <v-spacer></v-spacer>
    <v-hover v-slot="{ hover }">
      <v-btn plain outlined class="mx-2" :color="hover ? 'amber darker-2' : ''"
        >Buy</v-btn
      >
    </v-hover>
    <v-hover v-slot="{ hover }">
      <v-btn plain outlined class="mx-2" :color="hover ? 'amber darken-2' : ''"
        >Sell</v-btn
      >
    </v-hover>
    <v-spacer></v-spacer>

    <v-text-field
      dense
      outlined
      hide-details
      single-line
      color="amber darken-2"
    >
      <template v-slot:label>
        Search Properties by Area/Zip Code
      </template>
      <template v-slot:append>
        <v-icon right class="pa-2" color="amber darken-2">mdi-magnify</v-icon>
      </template>
    </v-text-field>

    <v-spacer></v-spacer>
    <v-badge right color="amber darken-1" dot overlap>
      <span slot="badge"></span>
      <!--slot can be any component-->
      <v-icon>mdi-message-reply-outline</v-icon>
    </v-badge>
    <v-btn class="mx-16 text-capitalize" outlined>
      <v-icon small left>mdi-account-outline</v-icon> Salah Uddin
      <v-icon small right>mdi-chevron-down</v-icon></v-btn
    >
  </v-app-bar>
</template>

<script>
export default {}
</script>

<style scoped>
.outline {
  color: "amber darken-2";
}
</style>
