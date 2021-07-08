<template>
  <v-sheet class="grey lighten-2" min-height="90vh">
    <property :image="image1" :status="status1" />
    <property :image="image1" :status="status2" />
    <property :image="image1" :status="status1" />
    <property :image="image1" :status="status3" />
  </v-sheet>
</template>

<script>
export default {
  data: () => ({
    image1:
      "https://images.unsplash.com/photo-1580587771525-78b9dba3b914?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8aG91c2UlMjBidWlsZGluZ3xlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80",
    status1: {
      name: "Fully Rented",
      color: "pink--text text--darken-1",
    },
    status2: {
      name: "Sold Out",
      color: "red--text text--accent-3",
    },
    status3: {
      name: "Under Construction",
      color: "yellow--text text--accent-4",
    },
  }),
}
</script>

<style lang="scss" scoped></style>
