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
    max-height: 60px;
    padding: 20px 5px;
}

footer .footer-top .my-col p {
    color: white;
    font-weight: bold;
    text-transform: uppercase;
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
    width: 25px;
    height: 25px;
}

footer .footer-bottom .div-icons .img-icons img {
    width: 100%;

}
</style>