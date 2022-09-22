<template>
  <footer class="margindefault">
    <div class=" bgimg container-fluid w-80 px-0">
    <div class="cont d-flex flex-row justify-content-evenly margin">
       <div class="d-flex py-5 px-3 m-0"> <div class="py-5 px-3 m-0">
            <ul class="text-white-50 list-unstyled text-start">
                <li><h4 class="text-white fw-bold">DC COMICS</h4></li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Video</li>
                <li>News</li>
            </ul>
            <ul class="text-white-50 list-unstyled text-start">
                <li><h4 class="text-white fw-bold">SHOP</h4></li>
                <li>Shop DC</li>
                <li>Shop DC Collectibless</li>
            </ul>
        </div>
        <div class="py-5 px-3 m-0">
            <ul class="text-white-50 list-unstyled text-start">
                <li><h4 class="text-white fw-bold">DC COMICS</h4></li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Video</li>
                <li>News</li>
            </ul>
        </div>
        <div class=" py-5 px-3 m-0">
            <ul class="text-white-50 list-unstyled text-start">
                <li><h4 class="text-white fw-bold">SITES</h4></li>
                <li>DC </li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div></div>
        <div class="img py-5 px-3 m-0">
            <img  src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
    <div class="bggrey d-flex flex-row justify-content-evenly margin">
        <div class="d-flex align-items-center">
            <button class="btn border border-3 border-primary p-3 text-white fw-bold">SING-UP NOW</button>
        </div>
        <div class="d-flex gap-3 align-items-center">
            <h4 class="text-primary fw-bold m-0">FOLLOW US</h4>
           <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
            <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
            <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
            <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
            <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
        </div>
    </div>
    </div>
  </footer>
</template>

<script>
export default {
name:'FooterDc'
}
</script>

<style scoped lang="scss">
     .margindefault{
        margin: 0 auto;
    }
    .img{
        margin-left: 30%;
        height: 100%;
        img{
            height: 100%; 
        }
       
    }
    .bgimg{
        width: 100%;
        height: 500px;
        background-image: url(../assets/img/footer-bg.jpg);
        background-size:100%;
        .cont{
            width: 100%;
            height: 100%;
        }
    }
.margin{
    margin-left: 10%;
}
li:hover{
    cursor: pointer;
    color: white!important;
}
.bggrey{
    height: 150px;
    background-color: rgb(76, 77, 77);
}
</style>