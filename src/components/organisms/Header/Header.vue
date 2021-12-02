<template>
  <header class="header">
    <WidthContainer>
      <div class="header__inner">
        <div class="header__logo">
          <router-link to="/">LOGO</router-link>
        </div>
        <div class="header__nav">
          <router-link to="/about">About</router-link>
        </div>
      </div>
    </WidthContainer>
  </header>
</template>

<script lang="ts">
import { Vue, Component } from "@/utils/vue-imports";
import WidthContainer from "@/components/atoms/WidthContainer/WidthContainer.vue";

@Component({
  name: "Header",
  components: {
    WidthContainer,
  },
})
export default class Header extends Vue {}
</script>

<style lang="scss" scoped>
@import url("./Header.scss");
</style>
