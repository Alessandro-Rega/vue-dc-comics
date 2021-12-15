<template>
  <div id="app">
    <Navbar/>
    <Main/>
    <SectionMain/>
    <FooterTop/>
    <FooterBottom/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Main from './components/Main.vue'
import SectionMain from './components/SectionMain.vue'
import FooterTop from './components/FooterTop.vue'
import FooterBottom from './components/FooterBottom.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Main,
    SectionMain,
    FooterTop,
    FooterBottom,
  },
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #1f1f1f;
  padding-top: 20px;
}
</style>
