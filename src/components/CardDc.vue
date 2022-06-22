<template>
    <div>
        <div class="aspect">
            <img :src="image" alt="">
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

<style>
    .aspect{
        aspect-ratio: 1/1;
        overflow: hidden;
        margin-bottom: 1rem;
    }
</style>