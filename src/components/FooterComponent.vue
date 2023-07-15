<script>
export default {
    name: "FooterComponent",
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
    <footer>
        <section class="footer-top">
            <div class="container row">
                <div class="my-col">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                    <p>
                        Digital comics
                    </p>
                </div>
                <div class="my-col">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
                    <p>
                        DC Merchandise
                    </p>
                </div>
                <div class="my-col">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">
                    <p>
                        Subscription
                    </p>
                </div>
                <div class="my-col">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="locator">
                    <p>
                        Comic shop locator
                    </p>
                </div>
                <div class="my-col">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="power visa">
                    <p>
                        DC Power Visa
                    </p>
                </div>
            </div>
        </section>

        <section class="footer-center">
            <div class="container">
                <div class="row">
                    <div class="col-sx">
                        <div class="second-row">
                            <div class="list-col">
                                <div class="list-top">
                                    <h2>
                                        DC COMICS
                                    </h2>
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
                                    </ul>
                                </div>
                                <div class="list-bottom">
                                    <h2>
                                        SHOP
                                    </h2>
                                    <ul>
                                        <li>
                                            Shop DC
                                        </li>
                                        <li>
                                            Shop DC Collectibles
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <div class="list-col">
                                <h2>
                                    DC
                                </h2>
                                <ul>
                                    <li>
                                        Terms of Use
                                    </li>
                                    <li>
                                        Privacy policy (New)
                                    </li>
                                    <li>
                                        Ad Choices
                                    </li>
                                    <li>
                                        Advertising
                                    </li>
                                    <li>
                                        Jobs
                                    </li>
                                    <li>
                                        Subscriptions
                                    </li>
                                    <li>
                                        Talent Workshops
                                    </li>
                                    <li>
                                        CPSC Certificates
                                    </li>
                                    <li>
                                        Ratings
                                    </li>
                                    <li>
                                        Shop Help
                                    </li>
                                    <li>
                                        Contact Us
                                    </li>
                                </ul>
                            </div>
                            <div class="list-col">
                                <h2>
                                    SITES
                                </h2>
                                <ul>
                                    <li>
                                        DC
                                    </li>
                                    <li>
                                        MAD Magazine
                                    </li>
                                    <li>
                                        DC Kids
                                    </li>
                                    <li>
                                        DC Universe
                                    </li>
                                    <li>
                                        DC Power Visa
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="col-dx">
                        <div class="img-bg">
                            <img src="../assets/img/dc-logo-bg.png" alt="logo-bg">
                        </div>
                    </div>
                </div>
            </div>

        </section>

        <section class="footer-bottom">
            <div class="container">
                <div class="div-button">
                    <button>
                        SIGN UP NOW!
                    </button>
                </div>
                <div class="div-icons">
                    <a href="#">
                        FOLLOW US
                    </a>
                    <div class="img-icons">
                        <img src="../assets/img/footer-facebook.png" alt="Facebook">
                    </div>
                    <div class="img-icons">
                        <img src="../assets/img/footer-twitter.png" alt="Twitter">
                    </div>
                    <div class="img-icons">
                        <img src="../assets/img/footer-youtube.png" alt="You Tube">
                    </div>
                    <div class="img-icons">
                        <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                    </div>
                    <div class="img-icons">
                        <img src="../assets/img/footer-periscope.png" alt="Periscope">
                    </div>
                </div>
            </div>
        </section>

    </footer>
</template>

<style lang="scss" scoped>
footer .container {
    max-width: 1000px;
    margin: 0 auto;
}

footer .footer-top {
    background-color: #0282F9;
}

footer .footer-top .row {
    display: flex;
    justify-content: center;
}

footer .footer-top .my-col {
    width: calc(100% / 5);
    display: flex;
    align-items: center;
    margin: 0 5px;
}

footer .footer-top .my-col img {
    max-width: 60px;
    max-height: 85px;
    padding: 20px 5px;
}

footer .footer-top .my-col p {
    color: white;
    font-weight: bold;
    text-transform: uppercase;
}

footer .footer-center {
    background-image: url('../assets/img/footer-bg.jpg');
}

footer .footer-center .row {
    max-height: 350px;
    display: flex;
    justify-content: space-between;
}

footer .footer-center .col-sx {
    width: calc(100% / 3 * 2);
}



footer .footer-center .second-row {
    display: flex;
}

footer .footer-center h2 {
    color: white;
    padding: 10px 0;
}



footer .footer-center .second-row .list-col {
    margin-right: 40px;
}

footer .footer-center ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

footer .footer-center ul li {
    color: gray;
    padding: 3px 0;
}

footer .footer-center .img-bg {
    height: 100%;
}

footer .footer-center .img-bg img {
    width: 100%;
    height: 100%;
    object-fit: cover;

}


footer .footer-bottom {
    background-color: #303030;
}

footer .footer-bottom .container,
footer .footer-bottom .container .div-icons {
    display: flex;
    justify-content: space-between;
    align-items: center;
}


footer .footer-bottom .container .div-button button {
    padding: 10px;
    font-weight: bold;
    color: white;
    background-color: transparent;
    border: 1px solid #0282F9;
}

footer .footer-bottom .div-icons>* {
    padding: 20px 10px;
}

footer .footer-bottom .div-icons a {
    text-decoration: none;
    color: #0282F9;
    font-weight: bold;
}

footer .footer-bottom .div-icons .img-icons {
    width: 40px;
}

footer .footer-bottom .div-icons .img-icons img {
    width: 100%;

}
</style>