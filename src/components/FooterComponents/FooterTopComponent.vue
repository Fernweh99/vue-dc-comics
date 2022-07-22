<template>
  <div class="footer-top">
    <div class="row container">

      <div class="col">
        <h4>DC COMICS</h4>
      <ul>
        <li><a href="#">Character</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">News</a></li>
      </ul>
      <h4>SHOP</h4>
      <ul>
        <li><a href="#">Shop Dc</a></li>
        <li><a href="#">Shop Dc Collectibles</a></li>
      </ul>
      </div>

      <div class="col">
        <h4>DC</h4>
        <ul>
          <li><a href="#">Terms Of Use</a></li>
          <li><a href="#">Privacy policy (new)</a></li>
          <li><a href="#">ad Choices</a></li>
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Subscriptions</a></li>
          <li><a href="#">Talent Workshops</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Ratings</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>

      <div class="col">
        <h4>SITES</h4>
        <ul>
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Power Visa</a></li>
        </ul>
      </div>
      <div class="col-img">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterTopComponent'
}
</script>

<style lang="scss" scoped>
  .footer-top {
    background-image: url("../../assets/img/footer-bg.jpg");
  }
  .row {
    display: flex;
    position: relative;
  }
  .row .col {
    padding: 30px 0;
    margin-right: 25px;
  }
  .row .col-img {
    flex-grow: 1;
    background-image: url("../../assets/img/dc-logo-bg.png");
    background-repeat: no-repeat;
    background-position: right;
  }
  h4{
    margin: 15px 0;
  }
  ul li a {
    font-size: 12px;
    color: #6F7E85;
  }
</style>