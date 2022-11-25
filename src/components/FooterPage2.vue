<template>
  <div class="footer-2">
    <div>
      <button class="bottone">SIGN-UP NOW!</button>
    </div>
    <div class="icone">
      <h3>FOLLOW US</h3>
      <img src="img/footer-facebook.png" class="i" alt="">
      <img src="img/footer-twitter.png" class="i" alt="">
      <img src="img/footer-youtube.png" class="i" alt="">
      <img src="img/footer-pinterest.png" class="i" alt="">
      <img src="img/footer-periscope.png" class="i" alt="">

    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped lang="scss">
  .footer-2{
    display: flex;
    justify-content: space-between;
    background-color: black;
    padding: 20px;
  }
  .icone {
    display: flex;
  }
  .i {
    padding: 10px;
  }
  h3 {
    color: blue;
  }
  .bottone {
    color: white;
    background-color: black;
    padding: 10px;
    border: 3px solid blue;
  }
</style>
