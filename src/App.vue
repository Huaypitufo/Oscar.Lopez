<template>
  <div id="tooltipcontainer">
    <gl-search-box-by-click
      v-model="value"
      tooltip-container="#tooltipcontainer"
    />
  </div>
</template>

<script>
import * as components from "@gitlab/ui";

export default {
  name: "EmptyState",
  components: {
    ...components,
  },
};
</script>
