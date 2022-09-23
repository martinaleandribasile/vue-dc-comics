<template>
  <div id="app">
    <HeaderDc :linkarray='links'/>
    <JumbotroneDc/>
    <ContentDC :arrayComics='dcComics'/>
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
import {links} from '@/data/LinksHeader.js';
import{dcComics} from '@/data/dcComics.js'
import JumbotroneDc from '@/components/JumbotroneDC.vue'
export default {
  name: 'App',
  components: {
    HeaderDc,
    ContentDC,
    ShopDC,
    LinkCD,
    FooterDC,
    JumbotroneDc,
},
data(){
  return{
    links,
    dcComics
  }
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
  font-family: Helvetica, Arial, sans-serif;
  text-align: center;
}
.containerdef{
  width: 80%;
  margin: 0 auto;
}
button{
        cursor: pointer;
        &:hover{
            transform: scale(1.2)
        }
      }
</style>
