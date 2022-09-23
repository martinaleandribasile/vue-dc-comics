<template>
  <div class="comic">
    <div><img :src=ComicComponent.thumb alt=""></div>
    <h6>{{ComicComponent.series}}</h6>
  </div>
</template>

<script>
export default {
    name: 'cardDc',
    props:{
        ComicComponent : Object
        
}
}
</script>

<style scoped lang="scss">
    .comic{
        width: calc(100% / 6 - 30px);
        margin: 10px 0px;
        cursor: pointer;
        &:hover{
            transform: scale(1.1);
        }
        img{
            width: 100%;
            height: 270px;
        }
        h6{
            text-align: left;
            text-transform: uppercase;
            margin: 20px 0;
        }
    }

</style>