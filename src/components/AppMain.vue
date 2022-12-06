<script>
import AppServices from "./AppServices.vue";
import AppProject from "./AppProject.vue";
import AppPortofolio from "./AppPortofolio.vue";
export default {
  name: "AppMain",
  components: {
    AppServices,
    AppProject,
    AppPortofolio,
  },
};
</script>

<template>
  <main>
    <AppServices />
    <AppProject />
    <AppPortofolio />
  </main>
</template>

<style lang="scss" scoped></style>
