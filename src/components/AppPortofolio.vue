<script>
export default {
  name: "AppPortofolio",
};
</script>

<template>
  <section class="portfolio">
    <div class="container">
      <small class="my-red-title">Portfolio</small>
      <h1><strong>Latest</strong> Work</h1>
    </div>
    <div class="latest-project d-flex justify-content-between container">
      <div class="my-card">
        <img src="../assets/8wa60okr-1-790x576.jpg" alt="" class="img-fluid" />
        <div class="my-card-body d-flex justify-content-between">
          <p class="fw-bold">Basket of flower on the table</p>
          <small class="text-muted">Branding Strategy</small>
        </div>
      </div>
      <div class="my-card">
        <img src="../assets/DRY-1-790x576.jpg" alt="" class="img-fluid" />
        <div class="my-card-body d-flex justify-content-between">
          <p class="fw-bold">Purinky Products</p>
          <small class="text-muted">Digital Experience</small>
        </div>
      </div>
      <div class="my-card">
        <img
          src="../assets/a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg"
          alt=""
          class="img-fluid"
        />
        <div class="my-card-body d-flex justify-content-between">
          <p class="fw-bold">Satisfy Poster</p>
          <small class="text-muted">Branding Strategy</small>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.portfolio {
  margin: 60px 0;
}
img {
  border-radius: 20px;
}
.my-card {
  width: 400px;
  border-radius: 20px;
  box-shadow: 5px 5px 22px 30px rgba(244, 244, 244, 0.62);
  cursor: pointer;
}

.my-card:hover {
  background: linear-gradient(
    90deg,
    rgba(184, 38, 110, 1) 11%,
    rgba(243, 93, 107, 1) 100%
  );
  color: white;
  small {
    color: white !important;
  }
}
.my-card-body {
  p,
  small {
    padding: 10px;
    margin-top: 10px;
  }
}
.latest-project {
  margin-top: 50px;
}
</style>
