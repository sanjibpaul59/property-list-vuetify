<template>
  <v-btn
    large
    text
    plain
    class="grey--text text--darken-1 text-capitalize ml-2"
  >
    {{ btnName }}
    <v-icon right>{{ iconName }}</v-icon>
  </v-btn>
</template>

<script>
export default {
  props: {
    iconName: {
      type: String,
    },
    btnName: {
      type: String,
    },
  },
}
</script>

<style lang="scss" scoped></style>
