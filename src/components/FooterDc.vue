<template>
    <div class="contContents">
        <div class="containerdef">
            <div><button>SING-UP NOW</button></div>
            <div class="contsocial">
                <h2>FOLLOW US</h2>
                <a href=""><img src="../assets/img/footer-facebook.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-twitter.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-youtube.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-periscope.png" alt=""></a>
            </div>
        </div>
  </div>
</template>

<script>
export default {
name:'FooterDC'
}
</script>

<style scoped lang="scss">
 @mixin flexRowAlignCenter{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
.contContents{ 
    background-color: rgb(56, 56, 56);
    height: 150px; 
    .containerdef{
        height: 100%;
        justify-content: space-between;
    @include flexRowAlignCenter;
      button{
        cursor: pointer;
        background-color: rgb(56, 56, 56);
        border: 2px solid rgb(7, 138, 252);
        color: white;
        padding: 15px;
        &:hover{
            transform: scale(1.2)
        }
      }
      .contsocial{
        @include flexRowAlignCenter;
        h2{
            color: rgb(7, 138, 252);
            margin-right: 15px;
        }
        a{
            margin: 0 10px;
            cursor: pointer;
            &:hover{
            transform: scale(1.1)
        }
        }
      }
     
    }
}
</style>