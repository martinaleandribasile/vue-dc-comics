<template>
  <div class="containerdef">
   <div class="containerflex">
        <div class="containerimg">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="containerul">
            <ul>
                <li @click="changeActive(index)" v-for="(element,index) in linkarray" :key="element.name" :class="{active: element.active}"><a :class="{active: element.active}"  href="element.url">{{element.name}}</a></li>
            </ul>
        </div>
   </div>
  </div>
</template>

<script>

export default {
name: 'HeaderDc',
props:{
    linkarray:Array
},
data(){
    return{
        activeIndex : 0
    }
},
methods:{
    changeActive(i) {
        this.activeIndex = i
        this.linkarray.forEach((element,index)=>{
            if(this.activeIndex===index){
                element.active=true            
            }else{
                element.active=false
            }
        })
      
    }

}
}
</script>

<style scoped lang="scss">
    @mixin flexRowAlignCenter{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
    .containerflex{
        height: 150px;
        justify-content: space-between;
        @include flexRowAlignCenter;
        .containerul{
            height: 100%;
            ul{
                margin: 0;
                @include flexRowAlignCenter;
                gap: 40px;
                height: 100%;
                list-style: none;
                li{
                    cursor: pointer;
                    @include flexRowAlignCenter;
                    height: 100%;
                    &.active{
                        border-bottom: 5px solid blue;
                    }
                    a{
                        color: black;
                        text-decoration: none;
                        font-weight: bold;
                        &.active{
                        color: blue;
                        }
                    }
                }
            }
        }
    }

</style>