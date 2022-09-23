<template>
    <div class="contContents">
        <div class="containerdef">
            <div class="containerdef">
                <div class="containerlist">  
                    <ul>
                        <li><h3>DC COMICS</h3></li>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                    </ul>
                    <ul>
                        <li><h3>SHOP</h3></li>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Coll</a></li>
                    </ul>
                </div>
                <div class="containerlist">  
                    <ul>
                        <li><h3>DC</h3></li>
                        <li><a href="">Termo of use</a></li>
                        <li><a href="">Private Policy</a></li>
                        <li><a href="">Ad Choise</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certificate</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="containerlist">  
                    <ul>
                        <li><h3>SITES</h3></li>
                        <li><a href="">Termo of use</a></li>
                        <li><a href="">Private Policy</a></li>
                        <li><a href="">Ad Choise</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                    </ul>
                </div>
            </div>
            <div class="containerlogo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
  </div>
</template>

<script>
export default {
name:'LinkCD'
}
</script>

<style scoped lang="scss">
 @mixin flexRowAlignCenter{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
.contContents{ 
    overflow: hidden;
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    height: 500px; 
    .containerdef{
        height: 100%;
        display: flex;
        flex-direction: row;
        gap: 50px;
        .containerlist{
            margin-top:50px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            ul{
                text-align: start;
                list-style: none;
                li{
                    margin: 10px 0;
                    h3{
                        color: white;
                        padding: 10px 0;
                    }
                    a{
                        color: grey;
                        text-decoration: none;
                        &:hover{
                            color: white;
                        }
                    }
                }
              
            }
        }
        .containerlogo{
            margin-right: auto;
            align-self: end;
            img{
                height: 100%;
                width: auto;
            }
        }
    
    }
}
</style>