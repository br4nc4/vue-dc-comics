<template>
    <div>
        <div class="container-fluid bgFooter">
            <div class="container myContainer">
                <img src="/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

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
</style>