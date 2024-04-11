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
                <ul>
                    <li>CHARACTERS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>
        </div>
    </header>

</template>

<style scoepd lang="scss">

    header{
        height: 120px;
        background-color: white;
        
        .container{
            height: 100% !important;

            li{
                display: inline;
                margin-left: 25px;
                position: relative;

                &:hover{
                    color: #0282f9;
                }
            }
            
        }

    }


</style>