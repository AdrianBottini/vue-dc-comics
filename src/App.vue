<template>
  <div class="container">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeaderPage></HeaderPage>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import HeaderPage from './components/HeaderPage.vue';

export default {
  components: {
    // HelloWorld,
    HeaderPage,
  },
};
</script>

<style lang="scss">
.container {
  max-width: 1200px;
  margin: 0 auto;
}
</style>
