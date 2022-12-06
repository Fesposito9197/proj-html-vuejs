<script>
import AppHero from "./AppHero.vue";
export default {
  name: "AppHeader",
  components: {
    AppHero,
  },
  props: {
    info: Object,
  },
  data() {
    return {
      active: 0,
    };
  },
};
</script>

<template>
  <header>
    <div class="container d-flex justify-content-between">
      <img src="../assets/white-logo-2.png" alt="" />
      <div class="d-flex">
        <ul>
          <li v-for="(header, index) in info">
            {{ header }}
          </li>
        </ul>
        <button class="my-btn my-btn-blue">Sign in</button>
      </div>
    </div>
    <AppHero />
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #0a164f;
}
img {
  margin: 20px 0;
}
ul {
  list-style: none;
  color: white;
  display: flex;
  margin-top: 20px;
  align-items: center;
  li {
    margin-left: 30px;
    cursor: pointer;
  }
}
li:hover {
  color: #ef5a6c;
}
.my-btn {
  margin-left: 40px;
  margin-top: auto;
  margin-bottom: auto;
}
</style>
