<script>
import SingleSerie from './SingleSerie.vue';

export default {
    name: "MainComponent",
    data() {
        return {
            products: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book",
                },
                {
                    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel",
                },
                {
                    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel",
                },
            ]
        }
    },
    components: {
        SingleSerie
    }
}
</script>

<template>
    <main>
        <section class="main-top">
            <div class="jumbotron">
                <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
            </div>
        </section>
        <section class="main-bottom">
            <div class="container">
                <h1>
                    Current Series
                </h1>
                <div class="cards">
                    <SingleSerie class="card" v-for="(product, productIndex) in products" :key="productIndex"
                        :serieImg="product.thumb" :serieTitle="product.series" />
                </div>
                <div class="my-btn">
                    <a href="#">
                        LOAD MORE
                    </a>
                </div>
            </div>
        </section>

    </main>
</template>

<style lang="scss" scoped>
main .main-top .jumbotron {
    height: 400px;
}

main .main-top .jumbotron img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
}

main .main-bottom {
    background-color: #1C1C1C;
    padding: 30px 0;

    .container {
        text-align: center;
        max-width: 1000px;
        height: 100%;
        margin: 0 auto;
        position: relative;
    }

    h1 {
        text-transform: uppercase;
        font-weight: bold;
        color: white;
        background-color: #0282F9;
        padding: 10px;
        position: absolute;
        top: -50px;
    }

    .my-btn a {
        padding: 10px 30px;
        background-color: #0282F9;
        color: white;
        text-decoration: none;
        font-weight: bold;
        cursor: pointer;
    }
}

.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
</style>
