<script>
export default {
  name: "AppBlog",
};
</script>

<template>
  <section class="blogs container">
    <div class="text-center blogs-title">
      <small class="my-red-title">Blog</small>
      <h1><strong>Latest</strong> Posts</h1>
      <p>
        When, while the lovely valley teems with vapour around meand the
        meridian sun strikes the upper surface.
      </p>
    </div>
    <div class="d-flex justify-content-between">
      <div class="my-big-card">
        <div class="d-flex justify-content-between card-info align-items-end">
          <div class="text-white">
            <small>April 21, 2019 by Paul</small>
            <p class="fw-bold">Amazon get CCI nod to acquire 49% stake in</p>
            <p>
              When, while the lovely valley teems with vapour around meand the
              meridian sun s...
            </p>
          </div>
          <div><button class="my-btn">Read More</button></div>
        </div>
      </div>
      <div class="small-card text-white">
        <small>April 21, 2019 by Paul</small>
        <p class="fw-bold">
          Clearing corporations get SEBI nod to invest in overnight funds
        </p>
        <p>
          When, while the lovely valley teems with vapour around meand the
          meridian sun s...
        </p>
        <button class="my-btn">Read More</button>
      </div>
      <div class="small-card text-white">
        <small>April 21, 2019 by Paul</small>
        <p class="fw-bold">
          Shabnam Dhillion, wife of RSSB chief Gurinder Dhillon, passes away in
          London
        </p>
        <p>
          When, while the lovely valley teems with vapour around meand the
          meridian sun s...
        </p>
        <button class="my-btn">Read More</button>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.blogs {
  padding: 90px 0;
}
.card-info {
  padding-top: 170px;
}
.my-btn {
  padding: 5px 10px;
  color: black;
  background-color: white;
}
.small-card {
  width: 300px;
  padding: 30px;
  border-radius: 20px;
  background-color: #030331;
  small,
  p {
    margin-bottom: 20px;
  }
}
.my-big-card {
  width: 700px;
  height: 300px;
  border-radius: 20px;
  background-image: url(../assets/headway-537308-unsplash-1380x703.jpg);
  background-size: cover;
}
</style>
