<template>
  <div id="app">
    <nav-bar></nav-bar>
    <the-carousel></the-carousel>
    <middle-section></middle-section>
    <join-section></join-section>
    <the-footer-vue></the-footer-vue>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import TheCarousel from "./components/TheCarousel.vue";
import MiddleSection from "./components/MiddleSection.vue";
import JoinSection from "./components/JoinSection.vue";
import TheFooterVue from "./components/TheFooter.vue";
export default {
  name: "App",
  components: { NavBar, TheCarousel, MiddleSection, JoinSection, TheFooterVue },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
