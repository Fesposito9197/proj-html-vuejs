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
  data() {
    return {
      Header: ["Home", "About", "Services", "Blog", "Contact", "Portafolio"],
    };
  },
};
</script>

<template>
  <div>
    <AppHeaderVue :info="Header" />
    <AppMainVue />
    <AppFooterVue />
  </div>
</template>

<style lang="scss">
@import "./style/global.scss";
</style>
