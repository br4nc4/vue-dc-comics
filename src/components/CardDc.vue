<template>
    <div>
        <div class="card">
            <img class="card-img-top" :src="image" alt="">
            <div class="card-body">{{series}}</div>
        </div>
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

</style>