<script>

    export default {
        name: 'SingleCard',
        props: ["comic"],
    }

</script>

<template>


        <div class="col">
            <div class="card d-flex justify-content-center align-items-center" style="width: 12rem">
                <img :src="comic.thumb" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text"> {{ comic.series }} </p>
                </div>
            </div>
        </div>


</template>


<style scoped lang="scss">

    .card{
        background-color: transparent !important;
        border: 1px solid transparent !important;

        .card-img-top{
            width: 200px !important;
            height: 200px !important;
        }

        .card-text{
            color: white !important;
        }

    }


</style>