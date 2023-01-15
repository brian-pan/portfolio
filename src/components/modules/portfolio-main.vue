<template>
  <div class="portfolio-main">
    <div class="portfolio-main__heading">
      <div class="portfolio-main__heading-text">
        <h1>Hello!</h1>
        <h2>I'm Zifan Pan</h2>
      </div>
      <div class="portfolio-main__heading-icon-wrapper">
        <!-- <span>Scroll</span> -->
        <icon-chevron class="portfolio-main__heading-icon" :is-round="true" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import IconChevron from "../widgets/icons/icon-chevron.vue";

export default defineComponent({
  data() {
    return {};
  },
  components: {
    IconChevron,
  },
});
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

.portfolio-main {
  border: 1px solid red;

  @media #{$bp-tablet} {
    background-color: red;
  }
}

.portfolio-main__heading-icon {
  width: 25px;
  height: 25px;
  stroke-width: 3px;
}
</style>
