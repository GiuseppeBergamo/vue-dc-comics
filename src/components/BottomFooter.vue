<template>
  <div id="bottom-footer">
    <div class="container bottom-footer-container">
      <div class="button-container">
        <a href="#" class="button">SIGN-UP NOW!</a>
      </div>
      <div id="socials">
        <h3>FOLLOW US</h3>
        <img src="../assets/img/footer-facebook.png" alt="facebook">
        <img src="../assets/img/footer-periscope.png" alt="periscope">
        <img src="../assets/img/footer-pinterest.png" alt="pinterest">
        <img src="../assets/img/footer-twitter.png" alt="twitter">
        <img src="../assets/img/footer-youtube.png" alt="youtube">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BottomFooter',
}
</script>

<style>
  #bottom-footer{
    height: 100px;
    background-color: #303030;
  }

  .bottom-footer-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: nowrap;
  }

  .button-container{
    width: 20%;
  }

  .button{
    display: inline-block;
    padding: 10px;
    border: 2px solid #0282f9;
    color: white;
  }

  #socials{
    width: 40%;
    display: flex;
    justify-content: space-around;
  }

  #socials h3{
    color: #0282f9;
  }
</style>