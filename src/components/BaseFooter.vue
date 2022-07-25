<template>
  <footer>
    <FooterJumbotron></FooterJumbotron>
    <BottomFooter></BottomFooter>
  </footer>
</template>

<script>
import FooterJumbotron from './FooterJumbotron.vue';
import BottomFooter from './BottomFooter.vue';
export default {
    name: 'BaseFooter',
    components: { FooterJumbotron, BottomFooter }
}
</script>

<style>

</style>