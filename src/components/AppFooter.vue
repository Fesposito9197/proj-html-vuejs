<script>
import AppInfoFooter from "./AppInfoFooter.vue";
import AppCopyright from "./AppCopyright.vue";
export default {
  name: "AppFooter",
  components: {
    AppInfoFooter,
    AppCopyright,
  },
};
</script>

<template>
  <AppInfoFooter />
  <AppCopyright />
</template>

<style lang="scss" scoped></style>
