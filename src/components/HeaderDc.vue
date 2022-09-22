<template>
  <header  class="margindefault my-0 py-0 ">
    <div class="container-fluid heigth w-80">
        <div class="w-100 m-auto row heigth d-flex justify-content-between align-items-center">
            <div class="col-2 heigth d-flex align-items-center justify-content-end">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div class="col-8 heigth d-flex align-items-center justify-content-center">
                <nav class="navbar navbar-expand-lg heigth pad">
                    <div class="heigth collapse navbar-collapse d-flex justify-content-end " id="navbarNav">
                        <ul class="heigth navbar-nav gap-3">
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">CHARACTERS</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">COMICS</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">MOVIES</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">TV</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">GAMES</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">COLLECTIBLES</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">VIDEOS</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">FANS</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">NEWS</a>
                            </li>
                            <li class="nav-item d-flex align-items-center">
                                <a class="nav-link active fw-semibold" href="#">SHOP</a>
                            </li>
                        </ul>
                    </div>

                </nav>
            </div>
        </div>
    </div>
  </header>
</template>

<script>
export default {
    name:'HeaderDc',
    data(){
        return{
            
        }
    }

}
</script>

<style scoped lang="scss">
    .heigth{
        height: 100%;
    }
    header{
        height: 150px;
        margin: 0 auto;
        .pad{
             padding: 0!important;
                li{
                        &:hover{
                            border-bottom: 5px solid blue;
                        }
                        a:hover{
                            color: blue !important;;
                        }
                    }
             }

    }
  
</style>