<template>
  <div class="container-footer">
    <div class="footer">
      <h2>DC COMICS</h2>
      <p>Charcers</p>
      <p>Comics</p>
      <p>Movies</p>
      <p>TV</p>
      <p>Games</p>
      <p>Videos</p>
      <p>News</p>
      <h2 class="shop">SHOP</h2>
      <p>Shop DC</p>
      <p>Shop DC Collectibles</p>
    </div>
    <div class="footer">
      <h2>DC</h2>
      <p>Teams Of Use</p>
      <p>Add Choices</p>
      <p>Advesting</p>
      <p>Jobs</p>
      <p>Subcription</p>
      <p>Talent Workshop</p>
      <p>CPSC Certificates</p>
      <p>Ratings</p>
      <p>Shop Help</p>
      <p>Contact Us</p>
    </div>
    <div class="footer">
      <h2>SITES</h2>
      <p>DC</p>
      <p>MAD Magazine</p>
      <p>DC Kids</p>
      <p>DC Universe</p>
      <p>DC Power Visa</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style scoped lang="scss">
  .container-footer {
    background-image: url("../../public/img/footer-bg.jpg");
    background-size: cover;
    display: flex;

  }
  .footer {
    padding: 30px;
    margin-top: 10px;
    color: grey;
  }
  .shop {
    margin-top: 20px;
  }
  p{
    padding: 5px;
  }
  h2 {
    color: white;
  }
</style>
