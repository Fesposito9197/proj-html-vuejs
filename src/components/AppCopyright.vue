<script>
export default {
  name: "AppCopyright",
};
</script>

<template>
  <section class="copyright position-relative">
    <div class="container d-flex justify-content-between align-items-center">
      <div>
        <p class="text-muted">
          <i class="fa-regular fa-copyright"></i>2020 Phlox. All Rights
          Reserved.
        </p>
      </div>
      <div class="social text-white d-flex align-items-center">
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-linkedin-in"></i>
        <i class="fa-brands fa-facebook-f"></i>
        <i class="fa-brands fa-twitter"></i>
        <div class="position-absolute arrow">
          <i class="fa-solid fa-arrow-up circle bg-white text-dark"></i>
        </div>
        <i class="fa-regular fa-comment circle bg-celeste"></i>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.copyright {
  background-color: #0a164f;
  padding: 10px 0;
}
p {
  margin-top: 10px;
}
.arrow {
  top: -5%;
  bottom: 55%;
  right: 13%;
}
.circle {
  border-radius: 100%;
  height: 30px;
  width: 30px;
  line-height: 30px;
  text-align: center;
}
.bg-celeste {
  background-color: #527ceb;
  height: 50px;
  width: 50px;
  line-height: 50px;
}
.social {
  i {
    margin-left: 50px;
  }
}
</style>
