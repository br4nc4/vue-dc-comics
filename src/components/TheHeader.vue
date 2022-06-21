<template>
    <div class="container-fluid .bg-light">
        <header class="d-flex justify-content-between">
            <div>
                <img src="/img/dc-logo.png" alt="">
            </div>

            <nav>
                <ul class="nav">
                    <li class="nav-item">
                        <a class="nav-link" :href="link.href" v-for="(link, i) in navMenu" :key="i">{{link.name}}</a>
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