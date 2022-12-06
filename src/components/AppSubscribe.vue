<script>
export default {
  name: "AppSubrscribe",
};
</script>

<template>
  <section class="subscribe container">
    <div
      class="card-subscribe d-flex align-items-center justify-content-between"
    >
      <div class="text-white">
        <h2 class="fw-bold">We Offer Awesome Services</h2>
        <p>
          when,while lovely valley teems with apour around meand meridian sun
          strikes the upper surface
        </p>
      </div>
      <div class="sub d-flex justify-content-between">
        <div>
          <input
            type="text"
            name=""
            id=""
            placeholder="Enter Your Email Address"
          />
        </div>
        <div>
          <button class="my-btn my-btn-blue">Subscribe</button>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.card-subscribe {
  padding: 50px;
  border-radius: 20px;
  background-color: #ef5a6c;
}
.subscribe {
  top: 0;
  bottom: 0;
  transform: translate(10%, -24%);
}
.sub {
  width: 400px;
  padding: 10px 10px;
  border-radius: 36px;
  background-color: white;
  input {
    border: none;
  }
}
</style>
