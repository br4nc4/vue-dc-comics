<template>
    <div>
        <header class="container d-flex justify-content-between align-items-center">
            <div>
                <img src="/img/dc-logo.png" alt="">
            </div>

            <nav>
                <ul class="nav">
                    <li class="nav-item" v-for="(link, i) in navMenu" :key="i">
                        <a class="nav-link" :href="link.href">{{link.name}}</a>
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


</style>