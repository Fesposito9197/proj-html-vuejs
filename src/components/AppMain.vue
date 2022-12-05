<script>
import AppServices from "./AppServices.vue";
import AppProject from "./AppProject.vue";
export default {
  name: "AppMain",
  components: {
    AppServices,
    AppProject,
  },
};
</script>

<template>
  <div>
    <AppServices />
    <AppProject />
  </div>
</template>

<style lang="scss" scoped></style>
