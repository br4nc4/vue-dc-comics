<template>
    <div>
        <div class="aspect position-relative">
            <img :src="image" alt="">
            <div class="overlay">
                <div class="text-white h-100 d-flex align-items-center justify-content-center">
                    <h5>PRICE {{price}}</h5>
                </div>
            </div>
        </div> 
        <div class="text-white text-uppercase">{{series}}</div>
    </div>
</template>


<script>
export default {
    name: "CardDc",
    props: {
        series: String,
        image: String,
        type: String,
        price: String,
    },
};
</script>

<style lang="scss">
    .aspect{
        aspect-ratio: 1/1;
        overflow: hidden;
        margin-bottom: 1rem;
        &:hover{
            .overlay{
                opacity: 1;
            }
        }
    }

    .overlay{
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba($color: #1d1b1b, $alpha: 0.5);
        opacity: 0;
    }
</style>