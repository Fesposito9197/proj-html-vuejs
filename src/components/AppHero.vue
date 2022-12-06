<script>
export default {
  name: "AppHero",
};
</script>

<template>
  <section class="d-flex container justify-content-between mt-3">
    <div class="text-white business">
      <h2 class="fw-bold fs-1">Business Planning</h2>
      <h2 class="fw-light">Digital Technology</h2>
      <h2 class="fw-bold fs-1">
        Modern Solution! Tu non lo sai ma sei bellissimo
      </h2>
      <p class="fw-light">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper surface.
      </p>
      <button class="my-btn my-btn-red my-btn-lg">Try it now</button>
      <button class="my-btn my-btn-blue my-btn-lg">Explore More</button>
    </div>
    <div>
      <img src="../assets/header.png" alt="" class="w-100" />
    </div>
  </section>
</template>

<style lang="scss" scoped>
p {
  color: #047dab;
  margin: 50px 0;
  width: 400px;
}
.business {
  margin: auto 0;
}

.my-btn:last-child {
  margin-left: 20px;
}
</style>
