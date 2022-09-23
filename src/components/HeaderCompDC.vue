<template>
  <div class="containerdef">
   <div class="containerflex">
        <div class="containerimg">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="containerul">
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </div>
   </div>
  </div>
</template>

<script>
export default {
name: 'HeaderDc',
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
                    @include flexRowAlignCenter;
                    height: 100%;
                    &:hover{
                        border-bottom: 5px solid blue;
                    }
                    a{
                        color: black;
                        text-decoration: none;
                        font-weight: bold;
                        &:hover{
                        color: blue;
                        }
                    }
                }
            }
        }
    }

</style>