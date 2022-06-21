<template>
    <div>
        <div class="container-fluid myBlueBg">
            <div class="container d-flex justify-content-between align-items-center py-5">
                <div v-for="card in cardsLinks" :key="card">
                    <img class="cardImgOne" :src="card.img" alt="">
                    <span class="text-white">{{card.link}}</span>
                </div>
                <div>
                    <img class="cardImgTwo" src="/img/buy-comics-shop-locator.png" alt="">
                    <span class="text-white">COMIC SHOP LOCATOR</span>
                </div>
                <div>
                    <img class="cardImgThree" src="/img/buy-dc-power-visa.png" alt="">
                    <span class="text-white">DC POWER VISA</span>
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
                    img: "/img/buy-comics-merchandise.png",
                    link: "DC MERCHANDISE",
                },
                {
                    img: "/img/buy-comics-subscriptions.png",
                    link: "SUBSCRIPTION",
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
    .cardImgOne{
        width: 50px;
    }
    .cardImgTwo{
        width: 35px;
    }
    .cardImgThree{
        width: 55px;
    }
</style>