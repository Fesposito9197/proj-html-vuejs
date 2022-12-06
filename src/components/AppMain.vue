<script>
import AppServices from "./AppServices.vue";
import AppProject from "./AppProject.vue";
import AppPortofolio from "./AppPortofolio.vue";
import AppPricing from "./AppPricing.vue";
export default {
  name: "AppMain",
  components: {
    AppServices,
    AppProject,
    AppPortofolio,
    AppPricing,
  },
};
</script>

<template>
  <main>
    <AppServices />
    <AppProject />
    <AppPortofolio />
    <AppPricing />
  </main>
</template>

<style lang="scss" scoped></style>
