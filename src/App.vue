<script>
import Header from "@/components/Header.vue";
export default {
  components: { Header },
  name: "App",
};
</script>

<template>
  <Header />
  <div id="app">
    <img src="@/images/vue-logo.png" alt="vuelogo" class="vue-logo" />
    <h1>Welcome to Vue.js</h1>
    <h3 class="h3-intro">
      Become a coding ninja with the fatest-growing JavaScript framework
    </h3>
    <p class="btn-text-intro">Awesome!</p>
  </div>
</template>



<style>
#app {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 25px;
}
.vue-logo {
  width: 129px;
  height: 129px;
}
h1 {
  font-weight: 800;
  font-size: 50px;
  color: #2b2f30;
}
h3 {
  font-weight: 800;
  font-size: 14px;
  color: #000000;
}
.h3-intro {
  width: 309px;
  height: 40px;
  text-align: center;
}
.btn-text-intro {
  font-weight: 800;
  font-size: 14px;
  background-color: #34495e;
  color: #ffffff;
  padding: 10px 20px;
  border-radius: 15px;
  display: inline-block;
}
</style>