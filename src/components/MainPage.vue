<template>
    <div class="wrapper">
        <div class="main_img">
            <div class="text_container">
                <h1>Making brands stand out</h1>
                <h1>is our obsession</h1>
                <div class="rectangle"></div>
                <p>Let us help your brand stand out.</p>
                <img :src="x" alt="x" />
            </div>
        </div>
        <div class="main_text">
            <div class="text_container">
                <p>
                    Minimalist is a full-service digital creative agency located
                    in Ontorio Canada. We focus on design, consulting,
                    technology, and photography. We’ve been building unique
                    digital products, platforms, and experiences for the past 6
                    years. Let us help your company grow.
                </p>
                <button type="button">Get in Touch</button>
            </div>
        </div>
    </div>
</template>

<script setup>
import x from "../assets/x.png";
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Vollkorn&display=swap");
.wrapper {
    width: 100%;
    display: flex;
    flex-flow: nowrap column;
    .main_img {
        position: relative;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 391px;
        flex-shrink: 0;
        background-image: url("../assets/main_img.png");
        background-size: cover;
        background-position: center;
        object-fit: cover;
        background-repeat: no-repeat;
        color: #fff;
        .text_container {
            display: flex;
            flex-flow: wrap column;
            justify-content: center;
            align-content: center;
            h1 {
                color: #fff;
                text-align: center;
                font-family: Montserrat;
                font-size: 44px;
                font-style: normal;
                font-weight: 400;
                line-height: 55px;
                text-transform: uppercase;
            }
            .rectangle {
                width: 80px;
                height: 2px;
                flex-shrink: 0;
                background: #fff;
                margin: 28px auto 0;
            }

            p {
                color: rgba(255, 255, 255, 0.81);
                text-align: center;
                font-family: Vollkorn;
                font-size: 15px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                margin-top: 25px;
            }

            img {
                position: absolute;
                left: calc(50% - 26px);
                bottom: -26px;
                width: 52px;
                height: 52px;
                flex-shrink: 0;
            }
        }
    }

    .main_text {
        height: 289px;
        flex-shrink: 0;
        background: #fefec9;
        display: flex;
        flex-flow: wrap column;
        justify-content: center;
        align-items: center;
        .text_container {
            width: 60%;
            p {
                color: #47474f;
                text-align: center;
                font-family: Vollkorn;
                font-size: 18px;
                font-style: normal;
                font-weight: 400;
                line-height: 25px;
            }

            button {
                margin-top: 40px;
                width: 159px;
                height: 53px;
                flex-shrink: 0;
                color: #47474f;
                text-align: center;
                font-family: Vollkorn;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px; /* 125% */
                background: transparent;
                outline: none;
                border: 1px solid;
                border-radius: 5px;
            }
        }
    }
}

@media screen and (max-width: 625px) {
    .main_text {
        .text_container {
            width: 90% !important;
        }
    }
}
@media screen and (max-width: 418px) {
    .main_text {
        padding-top: 100px;
        .text_container {

            width: 90% !important;
        }
    }
}
</style>
