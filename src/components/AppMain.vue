<script>
import AppServices from "./AppServices.vue";
import AppProject from "./AppProject.vue";
import AppPortofolio from "./AppPortofolio.vue";
import AppPricing from "./AppPricing.vue";
import AppBlog from "./AppBlog.vue";
import AppTestimonial from "./AppTestimonial.vue";
import AppPartners from "./AppPartners.vue";

export default {
  name: "AppMain",
  components: {
    AppServices,
    AppProject,
    AppPortofolio,
    AppPricing,
    AppBlog,
    AppTestimonial,
    AppPartners,
  },
};
</script>

<template>
  <main>
    <AppServices />
    <AppProject />
    <AppPortofolio />
    <AppPricing />
    <AppBlog />
    <AppTestimonial />
    <AppPartners />
  </main>
</template>

<style lang="scss" scoped></style>
