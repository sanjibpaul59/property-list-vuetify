<template>
  <v-btn
    dense
    small
    depressed
    :outlined="outline"
    class="rounded-pill text-capitalize ma-1"
    :color="color"
    >{{ value }}</v-btn
  >
</template>

<script>
export default {
  props: {
    value: {
      type: String,
    },
    color: {
      type: String,
      default: "grey darken-2",
    },
    outline: {
      type: Boolean,
      default: true,
    },
  },
}
</script>

<style lang="scss" scoped></style>
