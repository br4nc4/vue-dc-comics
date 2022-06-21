<template>
    <div>
        <div class="container-fluid myBlueBg">
            <div class="container d-flex">
                <div v-for="card in cardsLinks" :key="card">
                    <img :src="card.img" alt="">
                    <span>{{card.link}}</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    data(){
        return{
            cardsLinks:
            [
                {
                    img: "/img/buy-comics-digital-comics.png",
                    link: "DIGITAL COMICS",
                },
                {
                    img: "/img/buy-comics-digital-comics.png",
                    link: "DIGITAL COMICS",
                },
                {
                    img: "/img/buy-comics-digital-comics.png",
                    link: "DIGITAL COMICS",
                },
                {
                    img: "/img/buy-comics-digital-comics.png",
                    link: "DIGITAL COMICS",
                },
                {
                    img: "/img/buy-comics-digital-comics.png",
                    link: "DIGITAL COMICS",
                },
            ]
        }
    }
}
</script>

<style>
    .myBlueBg{
        background-color: #0282f9;
    }
</style>