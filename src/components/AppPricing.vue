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
    <div class="container d-flex prices-card">
      <div class="price-card text-center">
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
      <div class="price-card text-center">
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
.price-title {
  padding: 30px 0;
}
.price-card {
  border-radius: 20px;
  background-color: #fefefe;
  padding: 20px;
  width: 400px;
  margin-left: 20px;

  cursor: pointer;
}
.prices-card {
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
  top: 100%;
}
.price-card:hover {
  background-color: #ef5a6c;
  color: white;
  .my-btn {
    background: white;
    color: #ef5a6c;
  }
}

.price {
  font-size: 80px;
}
</style>
