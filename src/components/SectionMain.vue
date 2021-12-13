<template>
  <div>
      <section>
        <div class="container">
          <div class="card">
            <img src="../assets/buy-comics-digital-comics.png" alt="digitale">
            <span>digital comics</span>
          </div>
          <div class="card">
            <img src="../assets/buy-comics-merchandise.png" alt=",erch">
            <span>dc merchandise</span>
          </div>
          <div class="card">
            <img src="../assets/buy-comics-subscriptions.png" alt="iscrizione">
            <span>subscription</span>
          </div>
          <div class="card">
            <img src="../assets/buy-comics-shop-locator.png" alt="mappe">
            <span>comic shop locator</span>
          </div>
          <div class="card">
            <img src="../assets/buy-dc-power-visa.svg" alt="visa">
            <span>dc power visa</span>
          </div>
        </div>
      </section>
  </div>
</template>

<script>
export default {
    name: 'SectionMain'
}
</script>

<style scoped>

div{
  background-color: #0880f8;
}

section{
  width: 70%;
  height: 190px;
  background-color: #0880f8;
  margin: 0 auto;
}

.container{
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.card{
  display: flex;
  align-items: center;
  margin: 0 10px;
  cursor: pointer;
}

span{
  color: white;
  text-transform: uppercase;
  margin-left: 15px;
  font-size: 15px;
}

img{
  height: 65px;
}

.card:last-child img{
  height: 50px;
}

</style>