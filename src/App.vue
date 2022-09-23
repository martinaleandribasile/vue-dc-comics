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
import ContentDC from './components/ContentsComp.vue';
import HeaderDc from './components/HeaderCompDC.vue';
import ShopDC from './components/ShopDC.vue';
import LinkCD from './components/LinkDC.vue';
import FooterDC from './components/FooterCompDC.vue';

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
