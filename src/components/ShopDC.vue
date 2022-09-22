<template>
    <div class="contContents">
        <div class="containerdef">
           <a>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
           </a>
           <a>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
           </a>
           <a>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTION</p>
           </a>
           <a>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATION</p>
           </a>
           <a>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
           </a>
        </div>
  </div>
</template>

<script>
export default {
name:'ShopDC',
}
</script>

<style scoped lang="scss">
    @mixin flexRowAlignCenter{
           display: flex;
           flex-direction: row;
           align-items: center;
       }
   .contContents{ 
       background-color: rgb(7, 138, 252);
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
                    padding: 10px;
                    border: 5px solid blue;
                    border-radius: 10px;
                }
                img{
                    height: 70px;
                    width: auto;
                    padding-right: 15px;
                }
                p{
                    color: white;
                }
            }
       }
   }
   </style>