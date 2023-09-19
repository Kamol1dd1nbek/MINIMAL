<template>
    <div class="wrapper">
        <div class="container">
            <div class="header">
                <h2>LET’s Get in touch</h2>
                <div class="rectangle"></div>
            </div>
            <div class="touch_cards">
                <div class="card">
                    <img src="../assets/location.png" alt="" class="icon" />
                    <h2>MEET US IN PERSON</h2>
                    <h3>8776 Juniper Street</h3>
                    <h3>Unit #204</h3>
                    <h3>Merriweather, Ontorio</h3>
                    <h3>Canada</h3>
                </div>

                <div class="card">
                    <img src="../assets/heart.png" alt="" class="icon" />
                    <h2>The traditional way</h2>
                    <h3>Email us</h3>
                    <h3 class="brli">contact@minimal.com</h3>
                    <h3>Contact form</h3>
                    <h3>Scroll down</h3>
                </div>
                <div class="card">
                    <img src="../assets/email.png" alt="" class="icon" />
                    <h2>Let’s get social</h2>
                    <div class="card_links">
                        <img src="../assets/facebook.png" alt="" />
                        <p>Facebook</p>
                    </div>
                    <div class="card_links">
                        <img src="../assets/twitter.png" alt="" />
                        <p>Twitter</p>
                    </div>
                    <div class="card_links">
                        <img src="../assets/in.png" alt="" />
                        <p>Linkedin</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>

@media (max-width: 769px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        flex-shrink: 0;
        background-image: url("../assets/back.jpg");
        background-size: cover;
        object-fit: cover;
        .container {
            padding-top: 40px;
            width: 95%;
            display: flex;
            justify-content: center;
            flex-flow: wrap row;
            flex-shrink: 0;
            .header {
                display: flex;
                justify-content: center;
                flex-flow: nowrap column;
                align-items: center;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                    margin-bottom: 43px;
                }
            }
        }
    }

    .touch_cards {
        display: flex;
        flex-flow: wrap row;
        justify-content: center;
        align-items: center;
        .card {
            width: 319.984px;
            margin-bottom: 40px;
            flex-shrink: 0;
            img {
                height: 60px;
                width: 70px;
            }
            h2 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 125% */
                text-transform: uppercase;
                margin-top: 23px;
                margin-bottom: 20px;
            }
        }
    }

    .touch_cards .card:nth-child(1) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px; /* 129.412% */
        }
    }

    .touch_cards .card:nth-child(2) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px;
        }
        .brli {
            margin-bottom: 22px;
        }
    }

    .touch_cards .card:nth-child(3) {
        display: flex;
        flex-flow: wrap column;
        align-items: center;
        .card_links {
            display: flex;
            width: 30%;
            margin-bottom: 11px;
            justify-content: flex-start;
            img {
                width: 14px;
                height: 14px;
                margin-right: 9px;
            }
            p {
                color: #212121;
                font-family: Vollkorn;
                font-size: 17px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 117.647% */
            }
        }
    }
}

@media (min-width: 770px) and (max-width: 990px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        flex-shrink: 0;
        background-image: url("../assets/back.jpg");
        background-size: cover;
        object-fit: cover;
        .container {
            padding-top: 40px;
            width: 95%;
            display: flex;
            justify-content: center;
            flex-flow: wrap row;
            flex-shrink: 0;
            .header {
                display: flex;
                justify-content: center;
                flex-flow: nowrap column;
                align-items: center;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                    margin-bottom: 43px;
                }
            }
        }
    }

    .touch_cards {
        display: flex;
        flex-flow: wrap row;
        justify-content: center;
        align-items: center;
        .card {
            width: 319.984px;
            margin-bottom: 40px;
            flex-shrink: 0;
            img {
                height: 60px;
                width: 70px;
            }
            h2 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 125% */
                text-transform: uppercase;
                margin-top: 23px;
                margin-bottom: 20px;
            }
        }
    }

    .touch_cards .card:nth-child(1) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px; /* 129.412% */
        }
    }

    .touch_cards .card:nth-child(2) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px;
        }
        .brli {
            margin-bottom: 22px;
        }
    }

    .touch_cards .card:nth-child(3) {
        display: flex;
        flex-flow: wrap column;
        align-items: center;
        .card_links {
            display: flex;
            width: 30%;
            margin-bottom: 11px;
            justify-content: flex-start;
            img {
                width: 14px;
                height: 14px;
                margin-right: 9px;
            }
            p {
                color: #212121;
                font-family: Vollkorn;
                font-size: 17px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 117.647% */
            }
        }
    }
}

@media (min-width: 991px) and (max-width: 1200px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 517px;
        flex-shrink: 0;
        background-image: url("../assets/back.jpg");
        background-size: cover;
        object-fit: cover;
        .container {
            width: 1000px;
            height: 379px;
            flex-shrink: 0;
            .header {
                display: flex;
                justify-content: center;
                flex-flow: wrap column;
                align-items: center;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                    margin-bottom: 43px;
                }
            }
        }
    }

    .touch_cards {
        display: flex;
        flex-flow: wrap row;
        justify-content: center;
        align-items: center;
        .card {
            width: 319.984px;
            height: 238px;
            flex-shrink: 0;
            img {
                height: 60px;
                width: 70px;
            }
            h2 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 125% */
                text-transform: uppercase;
                margin-top: 23px;
                margin-bottom: 20px;
            }
        }
    }

    .touch_cards .card:nth-child(1) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px; /* 129.412% */
        }
    }

    .touch_cards .card:nth-child(2) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px;
        }
        .brli {
            margin-bottom: 22px;
        }
    }

    .touch_cards .card:nth-child(3) {
        display: flex;
        flex-flow: wrap column;
        align-items: center;
        .card_links {
            display: flex;
            width: 30%;
            margin-bottom: 11px;
            justify-content: flex-start;
            img {
                width: 14px;
                height: 14px;
                margin-right: 9px;
            }
            p {
                color: #212121;
                font-family: Vollkorn;
                font-size: 17px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 117.647% */
            }
        }
    }
}

@media (min-width: 1201px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 517px;
        flex-shrink: 0;
        background-image: url("../assets/back.jpg");
        background-size: cover;
        object-fit: cover;
        .container {
            width: 1000px;
            height: 379px;
            flex-shrink: 0;
            .header {
                display: flex;
                justify-content: center;
                flex-flow: wrap column;
                align-items: center;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                    margin-bottom: 43px;
                }
            }
        }
    }

    .touch_cards {
        display: flex;
        flex-flow: wrap row;
        justify-content: center;
        align-items: center;
        .card {
            width: 319.984px;
            height: 238px;
            flex-shrink: 0;
            img {
                height: 60px;
                width: 70px;
            }
            h2 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 125% */
                text-transform: uppercase;
                margin-top: 23px;
                margin-bottom: 20px;
            }
        }
    }

    .touch_cards .card:nth-child(1) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px; /* 129.412% */
        }
    }

    .touch_cards .card:nth-child(2) {
        h3 {
            color: #212121;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px;
        }
        .brli {
            margin-bottom: 22px;
        }
    }

    .touch_cards .card:nth-child(3) {
        display: flex;
        flex-flow: wrap column;
        align-items: center;
        .card_links {
            display: flex;
            width: 30%;
            margin-bottom: 11px;
            justify-content: flex-start;
            img {
                width: 14px;
                height: 14px;
                margin-right: 9px;
            }
            p {
                color: #212121;
                font-family: Vollkorn;
                font-size: 17px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 117.647% */
            }
        }
    }
}
</style>
