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
            <div class="container">

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