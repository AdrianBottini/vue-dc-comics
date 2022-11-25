<template>
  <div class="container">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeaderPage></HeaderPage>
    <MainPage></MainPage>
    <FooterPage></FooterPage>
    <FooterPage2></FooterPage2>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import HeaderPage from './components/HeaderPage.vue';
import MainPage from './components/MainPage.vue';
import FooterPage from './components/FooterPage.vue';
import FooterPage2 from './components/FooterPage2.vue';

export default {
  components: {
    // HelloWorld,
    HeaderPage,
    MainPage,
    FooterPage,
    FooterPage2,
  },
};
</script>

<style lang="scss">
.container {
  margin: 0 auto;
}
</style>
