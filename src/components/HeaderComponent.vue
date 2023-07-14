<script>
export default {
    name: "HeaderComponent",
    data() {
        return {
        }
    },
    propos: {},
    methods: {

    }
}
</script>

<template>
    <header>
        <div class="header-logo">
            <img src="../assets/img/dc-logo.png" alt="logo-DC">
        </div>
        <div class="nav">
            <li>
                Characters
            </li>
            <li>
                Comics
            </li>
            <li>
                Movies
            </li>
            <li>
                Tv
            </li>
            <li>
                Games
            </li>
            <li>
                Collectibles
            </li>
            <li>
                Videos
            </li>
            <li>
                Fans
            </li>
            <li>
                News
            </li>
            <li>
                Shop
            </li>

        </div>
    </header>
</template>

<style lang="scss" scoped>
header .nav {
    text-transform: uppercase;
}
</style>