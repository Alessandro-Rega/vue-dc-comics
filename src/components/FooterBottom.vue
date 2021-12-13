<template>
  <div>
      <div class="container">
          <button class="btn">sign-up now!</button>
          <div class="social">
              <span>follow us</span>
              <img src="../assets/footer-facebook.png" alt="facebook">
              <img src="../assets/footer-twitter.png" alt="twitter">
              <img src="../assets/footer-youtube.png" alt="youtube">
              <img src="../assets/footer-pinterest.png" alt="pinterest">
              <img src="../assets/footer-periscope.png" alt="periscope">
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FooterBottom'
}
</script>

<style scoped>

.container{
    width: 70%;
    margin: 0 auto;
    height: 120px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.social{
    display: flex;
    align-items: center;
}

.btn{
    color: white;
    border: 2px solid #0880f8;
    background-color: #333333;
    padding: 10px 15px;
    text-transform: uppercase;
    font-size: 18px;
    cursor: pointer;
}

.btn:hover{
    background-color: rgb(80, 80, 80);
}

span{
    color: #0880f8;
    text-transform: uppercase;
    font-size: 18px;
    font-weight: bold;
    margin-right: 10px;
}

img{
    margin: 0 10px;
    cursor: pointer;
}

img:hover{
    filter: brightness(2);
}

</style>