<template>
  <div class="portfolio-main">
    <h1>Hello!</h1>
    <h2>I'm Zifan Pan</h2>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  data() {
    return {};
  },
});
</script>

<style lang="scss" scoped>
@import "../../styles/responsive.scss";

.portfolio-main {
  $border: 2px solid salmon;

  @media #{$bp-tablet} {
    background-color: red;
  }
}
</style>
