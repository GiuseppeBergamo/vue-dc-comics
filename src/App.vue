<template>
  <div id="app">
    <BaseHeader></BaseHeader>
    <TheMain></TheMain>
    <BaseFooter></BaseFooter>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue'
import TheMain from './components/TheMain.vue'
import BaseFooter from './components/BaseFooter.vue'


export default {
  name: 'App',
  components: {
    BaseHeader,
    TheMain,
    BaseFooter
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
