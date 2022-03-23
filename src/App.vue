<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <HeaderTop />
    <MainContent />
    <DcShop />
    <FooterTop />
    <FooterBottom />
  </div>
</template>

<script>
import HeaderTop from "./components/HeaderTop.vue";
import MainContent from "./components/MainContent.vue";
import DcShop from "./components/DcShop.vue";
import FooterTop from "./components/FooterTop.vue";
import FooterBottom from "./components/FooterBottom.vue";

export default {
  name: "App",
  components: {
    HeaderTop,
    MainContent,
    DcShop,
    FooterTop,
    FooterBottom,
  },
};
</script>

<style lang="scss">
@import "./assets/styles/style.scss";
</style>
