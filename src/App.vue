<template>
  <div class="container">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeaderPage></HeaderPage>
    <MainPage></MainPage>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import HeaderPage from './components/HeaderPage.vue';
import MainPage from './components/MainPage.vue';

export default {
  components: {
    // HelloWorld,
    HeaderPage,
    MainPage,
  },
};
</script>

<style lang="scss">
.container {
  margin: 0 auto;
}
</style>
