<script>
import AppHeaderVue from "./components/AppHeader.vue";
import AppMainVue from "./components/AppMain.vue";
import AppFooterVue from "./components/AppFooter.vue";
export default {
  components: {
    AppHeaderVue,
    AppMainVue,
    AppFooterVue,
  },
};
</script>

<template>
  <div>
    <AppHeaderVue />
    <AppMainVue />
    <AppFooterVue />
  </div>
</template>

<style lang="scss">
@import "./style/global.scss";
</style>
