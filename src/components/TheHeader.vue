<template>
    <div>
        <header class="container d-flex justify-content-between align-items-center py-3">
            <div>
                <img src="/img/dc-logo.png" alt="">
            </div>

            <nav>
                <ul class="nav myNav">
                    <li class="nav-item" v-for="(link, i) in navMenu" :key="i">
                        <a class="nav-link position-relative" :href="link.href">
                            <h6 class="mb-0 myLink">{{link.name}}</h6>
                        </a>
                    </li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>

export default{
    data(){
        return{
            navMenu:
            [
                {
                    name: "CHARACTERS",
                    href: "#",
                },
                {
                    name: "COMICS",
                    href: "#",
                },
                {
                    name: "MOVIES",
                    href: "#",
                },
                {
                    name: "TV",
                    href: "#",
                },
                {
                    name: "GAMES",
                    href: "#",
                },
                {
                    name: "COLLECTBLES",
                    href: "#",
                },
                {
                    name: "VIDEOS",
                    href: "#",
                },
                {
                    name: "FANS",
                    href: "#",
                },
                {
                    name: "NEWS",
                    href: "#",
                },
                {
                    name: "SHOP",
                    href: "#",
                },
            ]
        }
    }
}
</script>

<style lang="scss">
    .myNav{
            --bs-nav-link-padding-x: 1rem;
    --bs-nav-link-padding-y: 0.5rem;
    --bs-nav-link-font-weight: ;
    --bs-nav-link-color: black;
    --bs-nav-link-hover-color: #0282F9;
    --bs-nav-link-disabled-color: #6c757d;
    display: flex;
    flex-wrap: wrap;
    padding-left: 0;
    margin-bottom: 0;
    list-style: none;
    }

    .myLink:hover::after{
        background-color: #0282F9;
        bottom: 0;
        content: '';
        display: block;
        height: 5px;
        position: absolute;
        width: calc(100% - 32px);
        margin-bottom: -50px;
    }
</style>