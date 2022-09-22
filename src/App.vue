<template>
  <div id="app">
    <HeaderDc/>
    <ContentDC/>
    <ShopDC/>
    <LinkCD/>
    <FooterDC/>
  </div>
</template>

<script>
import ContentDC from './components/ContentsDc.vue';
import HeaderDc from './components/HeaderDc.vue';
import ShopDC from './components/ShopDC.vue';
import LinkCD from './components/LinkCD.vue';
import FooterDC from './components/FooterDC.vue';

export default {
  name: 'App',
  components: {
    HeaderDc,
    ContentDC,
    ShopDC,
    LinkCD,
    FooterDC,

}
}
</script>

<style lang="scss">
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.containerdef{
  width: 80%;
  margin: 0 auto;
}
</style>
