<template>
    <div>
        <div class="container-fluid bgFooter">
            <div class="container myContainer">
                <div class="row pt-5">
                    <div class="col-2 px-0 myCol">
                        <h5 class="text-white">DC COMICS</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in dcComicLinks" :key="link">
                                <a href="#" class="text-secondary text-decoration-none">
                                    <small>{{link.link}}</small>    
                                </a>
                            </li>
                        </ul>

                        <h5 class="text-white">SHOP</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in shopLinks" :key="link">
                                <a href="#" class="text-secondary text-decoration-none">
                                    <small>{{link.link}}</small>    
                                </a>
                            </li>
                        </ul>
                    </div>

                    <div class="col-2 px-0 myCol">
                        <h5 class="text-white">DC</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in dcLinks" :key="link">
                                <a href="#" class="text-secondary text-decoration-none">
                                    <small>{{link.link}}</small> 
                                </a>
                            </li>
                        </ul>
                    </div>

                    <div class="col-2 px-0 myCol">
                        <h5 class="text-white">SITES</h5>
                        <ul class="list-unstyled">
                            <li v-for="link in sitesLinks" :key="link">
                                <a href="#" class="text-secondary text-decoration-none">
                                    <small>{{link.link}}</small>    
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
                <img src="/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>

export default{
    data(){
        return{
            dcComicLinks:
            [
                {
                    link: "Characters",
                },
                {
                    link: "Comics",
                },
                {
                    link: "Movies",
                },
                {
                    link: "Tv",
                },
                {
                    link: "Games",
                },
                {
                    link: "Videos",
                },
                {
                    link: "News",
                },
            ],
            shopLinks:
            [
                {
                    link: "Shop DC",
                },
                {
                    link: "Shop DC Collectibles",
                },
            ],
            dcLinks:
            [
                {
                    link: "Terms Of Use",
                },
                {
                    link: "Privacy policy (New)",
                },
                {
                    link: "Ad Choices",
                },
                {
                    link: "Advertising",
                },
                {
                    link: "Jobs",
                },
                {
                    link: "Subscriptions",
                },
                {
                    link: "Talent Workshops",
                },
                {
                    link: "CPSC Certificates",
                },
                {
                    link: "Ratings",
                },
                {
                    link: "Shop Help",
                },
                {
                    link: "Contact Us",
                },
            ],
            sitesLinks:
            [
                {
                    link: "DC",
                },
                {
                    link: "MAD Magazine",
                },
                {
                    link: "DC Kids",
                },
                {
                    link: "DC Universe",
                },
                {
                    link: "DC Power Visa",
                },
            ]
        }
    }
}
</script>

<style>
    .bgFooter{
        background-image: url("/public/img/footer-bg.jpg");
    }

    .myContainer{
        height: 400px;
        position: relative;
        overflow: hidden;
    }

    .myContainer img{
        position: absolute;
        right: 0;
        top: -60px
    }

    .myCol{
        width: 160px !important; 
    }
</style>