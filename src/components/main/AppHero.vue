<script>
    export default{
        name: 'AppHero'
    }

</script>

<template>

    <section>
        <div class="container">
            <span>CURRENT SERIES</span>
        </div>
    </section>

</template>

<style scoped lang="scss">

        section{
            height: 600px;
            width: 100%;
            background-image: url('https://static.dc.com/2024-04/DC.com_20240412_WE_FemaleFuries_Marquee_3x1_.jpg?w=1200');
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            
            .container{
                height: 100%;
                position: relative !important;

                span{
                    cursor: pointer;
                    padding: 10px;
                    padding-left: 40px;
                    padding-right: 40px;
                    background-color: #0282f9;
                    color: white;
                    border: 1px solid transparent;
                    position: absolute;
                    top: 96%;
                    font-weight: 600;

                    &:hover{
                        font-size: 18px;
                    }
                }
            }
        }

</style>