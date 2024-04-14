<script>

    export default {
        name: 'AppInfoContacts'
    }

</script>

<template>

   <section id="info-contatti">
        <div class="container d-flex">
            <div class="d-flex align-items-center">
                <div class="d-flex"> 
                    <div>
                        <ul>
                            <li class="ms-title-li mb-2">DC COMICS</li>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <ul>
                            <li class="ms-title-li mb-2">SHOP</li>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <li class="ms-title-li mb-2">DC</li>
                            <li>Term Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <li class="ms-title-li mb-2">SITES</li>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div> 
                <div class="d-flex align-items-center ms-spazio">
                        <img src="../../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
   </section>

</template>

<style scoped lang="scss">

    section{
        width: 100%;
        background-image: url('../../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        overflow: none !important;

        .container{
            width: 100%;
            height: 100%;
            position: relative;

            ul{
                margin-top: 70px;
                margin-bottom: 70px;

                li{
                    list-style-type: none;
                    color: grey;

                    &:hover{
                        color: white;
                        cursor: pointer;
                    }
                }

            }

            .ms-title-li{
                color: white;
                font-size: 18px;
            }

            img{
                position: absolute;
                width: 48%;
                z-index: 1;
            }

            .ms-spazio{
                margin-left: 100px;
            }
           
        }
    }

</style>