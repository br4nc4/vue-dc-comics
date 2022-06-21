<template>
    <div>
        <div class="position-relative">
            <div class="bgFooter">
                <img class="jumboFooter" src="/img/footer-bg.jpg" alt="">
                <img src="/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<style>
    .bgFooter{
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    }

    .jumboFooter{
        width: 100%;
        height: 400px;
        object-fit: cover;
        object-position: top;
    }

    .bgFooter:last-child img{
        position: absolute;
        top: 0;
        right: 0;
    }
</style>