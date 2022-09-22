<template>
  <main class="margindefault">
<div class="container-fluid p-0 w-80">
    <div class="row w-100 margindefault">
        <div class="w-100 col-12 bg-dark height d-flex align-items-center justify-content-center">
            <p class="text-white fw-bold fs-4">-->  Content goes here!   &lt;--</p>
        </div>
        <div class="w-100 paddingx col-12 bg-primary height d-flex align-items-center ">
           <div class="d-flex align-items-center mx-auto justify-content-center n gap-5">
             <div class=" d-flex justify-content-center mx-3">
                <div class="imgcontainer me-3"><img src="../assets/img/buy-comics-digital-comics.png" alt="..."></div>
                <p class="card-text d-flex align-items-center text-white-50">DIGITAL COMICS</p>
            </div>
            <div class=" d-flex justify-content-center mx-3">
                <div class="imgcontainer me-3"><img src="../assets/img/buy-comics-merchandise.png" alt="..."></div>
                <p class="card-text d-flex align-items-center text-white-50">DC MERCHANDISE</p>
            </div>
            <div class=" d-flex justify-content-center mx-3">
                <div class="imgcontainer me-3"><img src="../assets/img/buy-comics-subscriptions.png" alt="..."></div>
                <p class="card-text d-flex align-items-center text-white-50">SUBSCRIPTION</p>
            </div>
            <div class=" d-flex justify-content-center mx-3">
                <div class="imgcontainer me-3"><img src="../assets/img/buy-comics-shop-locator.png" alt="..."></div>
                <p class="card-text d-flex align-items-center text-white-50">COMIC SHOP LOCATOR</p>
            </div>
            <div class=" d-flex justify-content-center mx-3">
                <div class="imgcontainer me-3"><img src="../assets/img/buy-dc-power-visa.svg" alt="..."/></div>
                <p class="card-text d-flex align-items-center text-white-50">DC POWER VISA</p>
            </div></div>
        </div>
    </div>
</div>
  </main>
</template>

<script>
export default {
name:'MainDc'
}
</script>

<style scoped lang="scss">
    .margindefault{
        margin: 0 auto;
    }
    img{
        width: 100%!important;
        height: 100%!important;
    }
    .height{
        height: 250px;
    }
    .imgcontainer{
        width: 90px;
        height: 90px;
    }
    .paddingx{
        padding: 100px 100px;
    }
    p{
        cursor: pointer;
    }
    p:hover{
        color: white!important;;
    }

</style>