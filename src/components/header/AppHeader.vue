<script>

    export default {
        name: 'AppHeader'
    }

</script>

<template>

    <header>
        <div class="container d-flex justify-content-between align-items-center">
            <div class="ms-box-image" >
                <img class="img-fluid mt-2 mb-2" src="../../assets/img/dc-logo.png" alt="Logo">
            </div>
            <div class="me-5">
                <span class="selected">CHARACTERS</span>
                <span class="selected">COMICS</span>
                <span class="selected">MOVIES</span>
                <span class="selected">TV</span>
                <span class="selected">GAMES</span>
                <span class="selected">COLLECTIBLES</span>
                <span class="selected">VIDEOS</span>
                <span class="selected">FANS</span>
                <span class="selected">NEWS</span>
                <span class="selected">SHOP</span>
            </div>
        </div>
    </header>

</template>

<style scoped lang="scss">

    header{
        height: 120px;
        background-color: white;
        
        .container{
            height: 100% !important;

            span{
                padding-bottom: 43px ;
                margin-left: 25px;
                cursor: pointer;
                position: relative;
                height: 100% !important;

                &:hover{
                    color: #0282f9;
                }

            }

            .selected:hover{
                border-bottom: 8px solid #0282f9;

            }

        }

    }


</style>