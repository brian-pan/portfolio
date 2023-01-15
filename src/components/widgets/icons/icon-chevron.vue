<template>
  <svg
    fill="none"
    stroke="currentColor"
    :stroke-linecap="isRound ? 'round' : ''"
    :stroke-linejoin="isRound ? 'round' : ''"
    viewBox="0 0 24 24"
    xmlns="http://www.w3.org/2000/svg"
    role="presentation"
  >
    <path d="M19 9l-7 7-7-7"></path>
  </svg>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    isRound: {
      type: Boolean,
      default: false,
    },
  },
});
</script>

<style lang="less" scoped></style>
