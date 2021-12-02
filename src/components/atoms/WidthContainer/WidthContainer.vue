<template>
  <div class="width-container">
    <slot />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "@/utils/vue-imports";

@Component({
  name: "WidthContainer",
})
export default class WidthContainer extends Vue {}
</script>

<style lang="scss" scoped>
@import url("./WidthContainer.scss");
</style>
