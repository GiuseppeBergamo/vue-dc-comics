<template>
  <div id="jumbotron">
    <div class="container footer-link-container">
      <div class="footer-links">
        <h4>DC COMICS</h4>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
      </div>
      <div class="footer-links">
        <h4>SHOP</h4>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <div class="footer-links">
        <h4>DC</h4>
        <ul>
          <li>Terms of use</li>
          <li>Privacy Policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshop</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <div class="footer-links">
        <h4>SITES</h4>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterJumbotron',
  data() {
    return 
  }
}
</script>

<style>
  #jumbotron {
    height: 500px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }

  .footer-link-container{
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    flex-wrap: wrap;
    align-content: flex-start;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right;
  }
  
  .footer-links {
    width: 10%;
    color: white;
    margin-bottom: 20px;
    margin-top: 20px;
  }

  .footer-links h4 {
    margin-bottom: 15px;
    font-size: 1.5rem;
  }

</style>