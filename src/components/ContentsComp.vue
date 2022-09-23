<template>
    <div class="contContents">
        <div class="containerdef">
            <div class="titleADV"> <h2>CURRENT SERIES</h2> </div>
            <div class="containercard" >
                <cardDc :ComicComponent="comicElement" v-for="comicElement in arrayComics" :key="comicElement.thumb"/>
            </div>
            <button>LOAD MORE</button>
        </div>
  </div>
</template>

<script>
import cardDc from "@/components/CardDc.vue"
export default {
name:'ContentDC',
components:{
    cardDc
},
props:{
    arrayComics:Array
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
  @mixin  flexColAlignCenter{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
.contContents{ 
    background-color: black;
    height: 850px; 
    .containerdef{
        height: 100%;
        position: relative;
    @include flexColAlignCenter;
    .titleADV{
        position: absolute;
        top: 0;
        transform: translate(0%,-50%);
        left: 0;
        padding: 15px 20px;
        background-color:  $colorlightblu;
        color: white;
    }
    .containercard{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            flex-wrap: wrap;
            color: white;
            font-weight: bold;
            margin: 0 auto;
            padding-top: 30px;
        }
    button{
        background-color: rgb(7, 138, 252);
        padding: 10px 30px;
        color: white;
    }
    }
}
</style>