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
        <div class="container">
            <div class="header-logo">
                <img src="../assets/img/dc-logo.png" alt="logo-DC">
            </div>
            <div class="nav">
                <ul>
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

                </ul>

            </div>
        </div>

    </header>
</template>

<style lang="scss" scoped>
header .container {
    max-width: 1000px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .header-logo {
    width: 60px;
    height: 60px;
}

header .header-logo img {
    width: 100%;
    height: 100%;
}

header .nav ul {
    list-style: none;
}

header .nav ul li {
    display: inline-block;
    margin: 5px 10px;
    text-transform: uppercase;
    font-weight: bold;
}
</style>