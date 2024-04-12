<script>

    export default {
        name: 'AppRegistrati'
    }

</script>

<template>

    <section>
        <div class="container d-flex justify-content-between align-items-center">
            <div>
                <button class="ms-btn">SIGN-UP NOW!</button>
            </div>
            <div class="d-flex align-items-center">
                <div class="ms-box-text me-4">
                    <span>FOLLOW US</span>
                </div>
                <div class="ms-box-image me-2">
                    <img class="rounded" src="../../assets/img/footer-facebook.png" alt="Facebook">
                </div>
                <div class="ms-box-image me-2">
                    <img class="rounded" src="../../assets/img/footer-twitter.png" alt="Twitter">
                </div>
                <div class="ms-box-image me-2">
                    <img class="rounded" src="../../assets/img/footer-youtube.png" alt="YouTube">
                </div>
                <div class="ms-box-image me-2">
                    <img class="rounded" src="../../assets/img/footer-pinterest.png" alt="Pinterest">
                </div>
                <div class="ms-box-image me-2">
                    <img class="rounded" src="../../assets/img/footer-periscope.png" alt="Maps">
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped lang="scss">

    section{
        background-color: #303030;
        height: 70px;
        position: relative;
        z-index: 2;

        .container{
            height: 100% !important;
            width: 100% !important;

            .ms-box-image{
            width: 30px;
            height: 30px;

                img{
                    width: 100% !important;
                    cursor: pointer;

                    &:hover{
                        background-color: white;
                    }
                }

            }

            .ms-box-text{
            color: #0282f9;

            }

            .ms-btn{
                cursor: pointer;
                padding: 10px;
                color: white;
                background-color: #303030;
                border: 2px solid #0282f9;

                    &:hover{
                        font-size: 18px;
                    }
            }
        }
     
    }

</style>