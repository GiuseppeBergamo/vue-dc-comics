<template>
  <div id="app">
    <BaseHeader></BaseHeader>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue'

export default {
  name: 'App',
  components: {
    BaseHeader
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
