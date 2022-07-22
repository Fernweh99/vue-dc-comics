<template>
  <div class="footer-bottom">
    <nav class="container">
      <div class="row">
        <div class="col">
          <a class="btn" href="#">SIGN-UP NOW!</a>
        </div>
        <div class="col-right">
          <h4>FOLLOW US</h4>
          <ul>
            <li><a href="#"><img src="../../assets/img/footer-facebook.png" alt="facebook icon" /></a></li>
            <li><a href="#"><img src="../../assets/img/footer-twitter.png" alt="twitter icon" /></a></li>
            <li><a href="#"><img src="../../assets/img/footer-youtube.png" alt="youtube icon" /></a></li>
            <li><a href="#"><img src="../../assets/img/footer-pinterest.png" alt="pinterest icon" /></a></li>
            <li><a href="#"><img src="../../assets/img/footer-periscope.png" alt="periscope icon" /></a></li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'FooterBottomComponent'
}
</script>

<style lang="scss" scoped>
  .footer-bottom{
    background-color: #303030;
  }
  nav {
    padding: 20px 0;
  }
  h4 {
    color: #0082F9;
  }
  .col-right {
    display: flex;
    align-items: center;
  }
  ul {
    display: flex;
  }
  ul li {
    margin-left: 20px;
  }
  .row {
    display: flex;
    align-items: center;
    justify-content:space-between;
  }
  a.btn {
    font-size: 14px;
    padding: 10px 15px;
    color: #fff;
    border: 1px solid #0082F9 ;
  }
</style>