<script>
import AppSubscribe from "./AppSubscribe.vue";
export default {
  name: "AppInfoFooter",
  components: {
    AppSubscribe,
  },
};
</script>

<template>
  <section class="info-footer position-relative">
    <AppSubscribe class="position-absolute" />
    <div class="container d-flex justify-content-between">
      <div class="info-col">
        <img src="../assets/white-logo-2.png" alt="" />
        <p class="text-muted mt-4">
          When, while the lovely valley teems with vapour around meand the
          meridian sun strikes the upper surface.
        </p>
      </div>
      <div class="info-col">
        <ul class="list-unstyled">
          <p class="fw-bold text-white">Quick Links</p>
          <li class="text-muted">Services</li>
          <li class="text-muted">Contact</li>
          <li class="text-muted">Blog</li>
        </ul>
      </div>
      <div class="info-col">
        <ul class="list-unstyled">
          <p class="fw-bold text-white">Resources</p>
          <li class="text-muted">Art Design</li>
          <li class="text-muted">Computer</li>
          <li class="text-muted">IT News</li>
          <li class="text-muted">Networkin</li>
          <li class="text-muted">Web Security</li>
        </ul>
      </div>
      <div class="info-col">
        <ul class="list-unstyled">
          <p class="fw-bold text-white">Contact Us</p>
          <li class="text-white">
            Address:
            <span class="text-muted">
              Patricia C.Amedee 4401 Waldeck Street Grapevine Nashville, Tx
              76051</span
            >
          </li>
          <li class="text-white">
            Phone:
            <span class="text-muted"> +99 (0) 101 0000 888</span>
          </li>
          <li class="text-white">
            Email:
            <span class="text-muted"> info@yourdomain.com</span>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.info-footer {
  background-color: #0a164f;
  padding-top: 180px;
  border-bottom: 1px solid grey;
}
.info-col {
  width: 30%;
  ul {
    li {
      margin-bottom: 10px;
    }
  }
}
</style>
