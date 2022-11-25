<template>
  <div class="card">
    <img :src="imgUrl" alt="">
    <h2>{{title}}</h2>
  </div>
</template>

<script>
export default {
  name: 'CardPage',
  props: {
    imgUrl: String,
    title: String,
  },
};
</script>

<style lang="scss" scoped>
.card {
  text-align: center;
  background-color: white;
  img {
    max-width: 90%;
  }
}
</style>
