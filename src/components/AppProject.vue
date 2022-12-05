<script>
export default {
  name: "AppProject",
};
</script>

<template>
  <section class="project">
    <div class="d-flex container justify-content-between mt-3">
      <div class="align-self-center col-left">
        <img src="../assets/men-data.png" alt="" class="" />
      </div>
      <div class="text-white business align-self-center col-right">
        <h2 class="fs-6 mb-5">Start your project</h2>
        <h2 class="fw-bold fs-1">Business Planning</h2>
        <h2 class="fw-light mb-5">Digital Technology</h2>
        <p class="fw-light mb-5">
          When, while the lovely valley teems with vapour around meand the
          meridian sun strikes the upper surface. of the impenetrable foliage of
          my trees, and but a few stray gleams steal into the inners sanctuary.
        </p>
        <button class="my-btn my-btn-red my-btn-lg">Try it now</button>
        <button class="my-btn my-btn-blue my-btn-lg">Explore More</button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.project {
  background-color: #0a164f;
  padding: 70px 0;
}
p {
  color: #047dab;
}
.col-right {
  margin-left: 220px;
}
.col-left {
  width: 70%;
  background-image: url(../assets/nemoodar.png);
  background-position: bottom;
  background-size: cover;
}
img {
  height: 300px;
  width: 300px;
}
.my-btn-blue {
  margin-left: 20px;
}
</style>
