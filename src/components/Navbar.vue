<template>
  <div>
    <header>
      <div class="container">
        <div class="cont-img">
          <img src="../assets/img/dc-logo.png" alt="logo dc">
        </div>
        <ul>
          <li>characters</li>
          <li class="selected">comics</li>
          <li>movies</li>
          <li>tv</li>
          <li>games</li>
          <li>collectibles</li>
          <li>videos</li>
          <li>fans</li>
          <li>news</li>
          <li>shop</li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>

header{
  height: 130px;
  background-color: #fff;
}

.container{
  width: 70%;
  height: 130px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.cont-img{
  width: min-content;
}


ul li{
  display: inline-block;
  text-transform: uppercase;
  margin: 0 10px;
  font-weight: bold;
  font-size: 15px;
  cursor: pointer;
  color: rgb(83, 83, 83);
}

.selected{
  color: #0880f8;
  position: relative;
}

.selected::after{
  content: "";
  position: absolute;
  bottom: -56px;
  left: 0;
  width: 100%;
  height: 10px;
  background-color: #0880f8;
}

</style>