<template>
  <div class="main">
    <div class="card">
      <img src="img/buy-comics-digital-comics.png" class="dc-card" alt="">
      <span>DIGITAL COMICS</span>
    </div>
    <div class="card">
      <img src="img/buy-comics-merchandise.png" class="dc-card" alt="">
      <span>DC MERCHANDAISE</span>
    </div>
    <div class="card">
      <img src="img/buy-comics-subscriptions.png" class="dc-card" alt="">
      <span>SUBCRIPTION</span>
    </div>
    <div class="card">
      <img src="img/buy-comics-shop-locator.png" class="dc-card" alt="">
      <span>COMIC SHOP LOCATOR</span>
    </div>
    <div class="card">
      <img src="img/buy-dc-power-visa.svg" class="dc-card" alt="">
      <span>DC POWER VISA</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainPage',
};
</script>

<style>
  .main{
    background-color: rgb(12,124,236);
    padding: 50px;
    margin-top: -22px;
    display: flex;
    justify-content: space-around;
  }
  .dc-card {
    width: 20%;
  }
  .card {
    display: flex;
  }
  span {
    color: white;
    display: flex;
    align-items: center;
    margin-left: 10px;
  }
</style>
