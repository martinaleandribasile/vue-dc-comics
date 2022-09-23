<template>
    <div class="contContents">
        <div class="containerdef">
           <a v-for='shop in shoplink' :key="shop.text">
                <img :src=shop.ind alt="">
                <p>{{shop.text}}</p>
           </a>
        </div>
  </div>
</template>

<script>
export default {
name:'ShopDC',
props:{
    shoplink:Array
}
}
</script>

<style scoped lang="scss">
    $colorlightblu: rgb(7, 138, 252);
    @mixin flexRowAlignCenter{
           display: flex;
           flex-direction: row;
           align-items: center;
       }
   .contContents{
       background-color: $colorlightblu;
       height: 200px; 
       .containerdef{
            height: 100%;
            @include flexRowAlignCenter;
            justify-content: space-between;
            a{
                cursor: pointer;
                width: calc(100% / 6 - 20px);
                margin: 0 10px;
                @include flexRowAlignCenter;
                &:hover{
                   transform: scale(1.2);
                }
                img{
                    height: 70px;
                    width: auto;
                    padding-right: 15px;
                }
                p{
                    color: white;
                    font-size: 13px;
                }
            }
       }
   }
   </style>