<template>
  <div id="app">
    <BaseHeader></BaseHeader>
    <TheMain></TheMain>
    <FooterJumbotron></FooterJumbotron>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue'
import TheMain from './components/TheMain.vue'
import FooterJumbotron from './components/FooterJumbotron.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    TheMain,
    FooterJumbotron,
}
}
</script>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;;
  }

  a {
    text-decoration: none;
    color: black;
  }

  li{
    list-style-type: none;
  }
  
  .container{
    margin: 0 auto;
    width: 1200px;
  }
</style>
