<script>
   
   export default {
        name: 'AppSectionBlue'
    }

</script>

<template>

    <section>
        <div class="container d-flex justify-content-evenly">
            
            <div class="d-flex justify-content-center align-items-center">
                <div class="ms-box-image me-2">
                    <img src="../../assets/img/buy-comics-digital-comics.png" alt="Buy-Smartphone">
                </div>
               <div class="ms-box-text">
                    <span>DIGITAL COMICS</span>
               </div>
            </div>

            <div class="d-flex justify-content-center align-items-center">
                <div class="ms-box-image me-2">
                    <img src="../../assets/img/buy-comics-merchandise.png" alt="Buy-Merchandise">
                </div>
               <div class="ms-box-text">
                    <span>DC MERCHANDISE</span>
               </div>
            </div>

            <div class="d-flex justify-content-center align-items-center">
                <div class="ms-box-image me-2">
                    <img src="../../assets/img/buy-comics-shop-locator.png" alt="Subscription">
                </div>
               <div class="ms-box-text">
                    <span>SUBSCRIPTION</span>
               </div>
            </div>

            <div class="d-flex justify-content-center align-items-center">
                <div class="ms-box-image me-2">
                    <img src="../../assets/img/buy-comics-subscriptions.png" alt="Map">
                </div>
               <div class="ms-box-text">
                    <span>COMIC SHOP LOCATOR</span>
               </div>
            </div>

            <div class="d-flex justify-content-center align-items-center">
                <div class="ms-box-image me-2">
                    <img src="../../assets/img/buy-dc-power-visa.svg" alt="Card">
                </div>
               <div class="ms-box-text">
                    <span>DC POWER VISA</span>
               </div>
            </div>

        </div>
    </section>

</template>

<style scoped lang="scss">

    section{
        height: 150px;
        background-color: #0282f9;
        
        .container{
            height: 100% !important;
            width: 100% !important;

            .ms-box-image{
            width: 60px;
            height: 60px;

                img{
                    width: 100% !important;
                }

            }

            .ms-box-text{
            color: white;
            }

        }
     
    }
        
       

</style>