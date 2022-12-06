<script>
export default {
  name: "AppPricing",
};
</script>

<template>
  <section class="price-list position-relative">
    <div class="text-center text-white price-title">
      <small class="my-red-title">Price List</small>
      <h1><strong>Our</strong> Pricing</h1>
      <p>
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper surface.
      </p>
    </div>
    <div class="container d-flex prices-card justify-content-between">
      <div class="price-card text-center">
        <div class="big-price">40</div>
        <h2 class="fw-bold">Designing</h2>
        <p class="fw-semibold">PROCESS</p>
        <i class="fa-solid fa-dollar-sign"></i>
        <h2 class="fw-bold price">40</h2>
        <p>Per Month</p>
        <ul class="list-unstyled">
          <li><strong>Creative</strong> Design Enabled</li>
          <li><strong>Vibrant</strong> Color Usage</li>
          <li><strong>Eye</strong> Catching Design</li>
          <li><strong>Extreme</strong> Typography</li>
          <li><strong>Exceptional</strong>Design</li>
        </ul>
        <button class="my-btn my-btn-lg my-btn-red">
          Order Now <i class="fa-solid fa-arrow-right"></i>
        </button>
      </div>
      <div class="price-card text-center position-relative">
        <div class="big-price">60</div>
        <h2 class="fw-bold">Devolping</h2>
        <p class="fw-semibold">PRODUCT</p>
        <i class="fa-solid fa-dollar-sign"></i>
        <h2 class="fw-bold price">60</h2>
        <p>Per Month</p>
        <ul class="list-unstyled">
          <li><strong>Creative</strong> Design Enabled</li>
          <li><strong>Vibrant</strong> Color Usage</li>
          <li><strong>Eye</strong> Catching Design</li>
          <li><strong>Extreme</strong> Typography</li>
          <li><strong>Exceptional</strong>Design</li>
        </ul>
        <button class="my-btn my-btn-lg my-btn-red">
          Order Now <i class="fa-solid fa-arrow-right"></i>
        </button>
      </div>
      <div class="price-card text-center">
        <div class="big-price">80</div>
        <h2 class="fw-bold">Supporting</h2>
        <p class="fw-semibold">CLIENTS</p>
        <i class="fa-solid fa-dollar-sign"></i>
        <h2 class="fw-bold price">80</h2>
        <p>Per Month</p>
        <ul class="list-unstyled">
          <li><strong>Creative</strong> Design Enabled</li>
          <li><strong>Vibrant</strong> Color Usage</li>
          <li><strong>Eye</strong> Catching Design</li>
          <li><strong>Extreme</strong> Typography</li>
          <li><strong>Exceptional</strong>Design</li>
        </ul>
        <button class="my-btn my-btn-lg my-btn-red">
          Order Now <i class="fa-solid fa-arrow-right"></i>
        </button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.price-list {
  background-color: #0a164f;
  padding-bottom: 240px;
}
.big-price {
  z-index: 99;
  top: -113px;
  position: absolute;
  color: #00000038;
  font-size: 250px;
  margin-left: 30px;
  font-weight: bold;
}
.price-title {
  padding: 30px 0;
}
.price-card {
  border-radius: 20px;
  background-color: #fefefe;
  padding: 20px;
  width: 330px;
  margin-left: 20px;
  box-shadow: 0px 50px 50px 4px rgba(0, 0, 0, 0.09);
  cursor: pointer;
  ul {
    margin-top: 70px;
  }
}
.prices-card {
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
  top: 100%;
}
.price-card:hover {
  background: linear-gradient(
    164deg,
    rgba(184, 38, 110, 1) 48%,
    rgba(243, 93, 107, 1) 100%
  );
  color: white;
  .my-btn {
    background: white;
    color: #ef5a6c;
  }
  .big-price {
    color: #e9ecef42;
  }
}

.price {
  font-size: 80px;
}
</style>
