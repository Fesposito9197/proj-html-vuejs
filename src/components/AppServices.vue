<script>
export default {
  name: "AppServices",
};
</script>

<template>
  <section class="service">
    <div class="text-center">
      <small class="my-red-title">Our Services</small>
      <h1><strong>What</strong> We Do</h1>
      <p>When, while the lovely valley teems with vapour around meand the</p>
    </div>
  </section>
  <section class="d-flex container justify-content-between service-cards">
    <div class="service-card position-relative">
      <div class="img-box position-absolute">
        <img src="../assets/Group-247.png" alt="" class="img-fluid" />
      </div>
      <h4 class="fw-bold text-center">Data Analysis</h4>
      <p class="text-center">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper
      </p>
      <i class="fa-solid fa-arrow-right circle position-absolute"></i>
    </div>
    <div class="service-card position-relative">
      <div class="img-box position-absolute">
        <img src="../assets/Group-567.png" alt="" class="img-fluid" />
      </div>
      <h4 class="fw-bold text-center">SEO Optimization</h4>
      <p class="text-center">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper
      </p>
      <i class="fa-solid fa-arrow-right circle position-absolute"></i>
    </div>
    <div class="service-card position-relative">
      <div class="img-box position-absolute">
        <img src="../assets/Group-538.png" alt="" class="img-fluid" />
      </div>
      <h4 class="fw-bold text-center">Security Data</h4>
      <p class="text-center">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper
      </p>
      <i class="fa-solid fa-arrow-right circle position-absolute"></i>
    </div>
    <div class="service-card position-relative">
      <div class="img-box position-absolute">
        <img src="../assets/Group-566.png" alt="" class="img-fluid" />
      </div>
      <h4 class="fw-bold text-center">Branding Strategy</h4>
      <p class="text-center">
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper
      </p>
      <i class="fa-solid fa-arrow-right circle position-absolute"></i>
    </div>
  </section>
  <section class="text-center service-btn">
    <button class="my-btn my-btn-lg my-btn-red">View All Services</button>
  </section>
</template>

<style lang="scss" scoped>
.service {
  margin: 80px 0;
  padding-bottom: 100px;
}

.img-box {
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  padding: 20px;
  border-radius: 20px;
  top: -70px;
  left: 10%;
  right: 10%;
}
.service-card {
  border-radius: 20px;
  width: 20%;
  padding: 80px 20px 20px 20px;
  cursor: pointer;
  h4 {
    margin-bottom: 20px;
  }
}
i {
  color: white;
  left: 45%;
  bottom: -6%;
}
.service-card:hover {
  background-color: #0a164f;
  color: white;
  .img-box {
    background-color: white;
    box-shadow: 0px 50px 50px 4px rgba(0, 0, 0, 0.09);
  }
  i {
    background: linear-gradient(
      90deg,
      rgba(184, 38, 110, 1) 11%,
      rgba(243, 93, 107, 1) 100%
    );
  }
}

.service-btn {
  margin-top: 200px;
  margin-bottom: 50px;
}
</style>
