<template>
  <div id="app" class="my-0 py-0">
    <div><HeaderDc/>
   <MainDc/>
   <FooterDc/></div>
  </div>
</template>

<script>
import HeaderDc from './components/HeaderDc.vue';
import MainDc from './components/MainDc.vue';
import FooterDc from './components/FooterDc.vue';
export default {
  name: 'App',
  components: {
    HeaderDc,
    MainDc,
    FooterDc
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  div{
    margin: 0 auto;
  }
}
</style>
