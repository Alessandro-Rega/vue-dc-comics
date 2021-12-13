<template>
  <div class="bg">
    <div class="cont-liste">
        <div class="lista-sinistra">
            <div class="lista-1">
                    <h3>dc comics</h3>
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
            <div class="lista-2">
                    <h3>shop</h3>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
            </div>
        </div>
        <div class="lista-centrale">
            <h3>dc</h3>
            <ul>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contacs Us</li>
            </ul>
        </div>
        <div class="lista-destra">
            <h3>dc</h3>
            <ul>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>
    </div>
    <div class="logo-fine">
        <img src="../assets/dc-logo-bg.png" alt="logo">
    </div>
  </div>
</template>

<script>
export default {
    name: 'FooterTop'
}
</script>

<style scoped>

.bg{
    width: 100%;
    height: 400px;
    background-image: url("../assets/footer-bg.jpg");
    background-repeat: no-repeat;
    background-position: 0 -30px;
    background-size: cover;
    position: relative;
    display: flex;
}

.logo-fine{
    width: 100%;
    height: 100%;
    position: relative;
    overflow: hidden;
}

img{
    position: absolute;
    right: 280px;
    top: -95px;
    overflow: hidden;
}

/* LISTA */
.cont-liste{
    width: 70%;
    margin: 0 0 0 15%;
    display: flex;
    padding: 30px 0;
}

.lista-centrale{
    margin: 0 40px;
}

h3{
    color: white;
    text-transform: uppercase;
    margin-top: 15px;
    margin-bottom: 5px;
}

ul li{
    font-size: 14px;
    color: gray;
    list-style: none;
    cursor: pointer;
    padding: 4px 0;
}

li:hover{
    color: lightgray;
}

</style>