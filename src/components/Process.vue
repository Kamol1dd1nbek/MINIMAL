<template>
    <div class="wrapper">
        <div class="container">
            <div class="page_title">
                <h1>How we make brands thrive</h1>
                <div class="rectangle"></div>
            </div>

            <div class="process-cards">
                <div class="proces-cards_item">
                    <div class="proces-cards_item-img">
                        <img :src="make_1" alt="make_1" />
                    </div>
                    <div class="process-cards_card-title">
                        <h2>SET a target</h2>
                    </div>
                    <div class="process-cards_card-description">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing
                            elit. Suspendisse varius enim in eros elementum
                            tristique.
                        </p>
                    </div>
                </div>
                <div class="proces-cards_item">
                    <div class="proces-cards_item-img">
                        <img :src="make_2" alt="make_1" />
                    </div>
                    <div class="process-cards_card-title">
                        <h2>design a solution</h2>
                    </div>
                    <div class="process-cards_card-description">
                        <p>
                            Duis cursus, mi quis viverra ornare, eros dolor
                            interdum nulla, ut commodo diam libero vitae erat.
                        </p>
                    </div>
                </div>
                <div class="proces-cards_item">
                    <div class="proces-cards_item-img">
                        <img :src="make_3" alt="make_1" />
                    </div>
                    <div class="process-cards_card-title">
                        <h2>track the progress</h2>
                    </div>
                    <div class="process-cards_card-description">
                        <p>
                            Aenean faucibus nibh et justo cursus id rutrum lorem
                            imperdiet. Nunc ut sem vitae risus tristique
                            posuere.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import make_1 from "../assets/make_1.png";
import make_2 from "../assets/make_2.png";
import make_3 from "../assets/make_3.png";
// navigator.onLine
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Vollkorn&display=swap");

@media screen and (max-width: 567px) {
    .wrapper {
        display: flex;
        width: 100%;
        height: 1400px;
        justify-content: center;
        // align-items: center;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap row;
            width: 90%;
            margin-top: 100px;
            .page_title {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;

                h1 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-top: 0px;
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

            .process-cards {
                display: flex;
                flex-flow: wrap column;
                width: 100%;
                gap: 40px;
                .proces-cards_item {
                    height: 368px;
                    width: 90%;
                    display: flex;
                    justify-content: space-between;
                    flex-direction: column;
                    margin: 0 auto;
                    .proces-cards_item-img {
                        margin-top: 0 !important;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        width: 95%;
                        margin: auto;
                        height: 219px;
                        background: #f5f5f5;
                        margin-bottom: 38px;
                        img {
                            transition: all 0.3s linear;
                        }
                        &:hover img {
                            transform: scale(1.1);
                        }
                    }

                    .process-cards_card-title h2 {
                        color: #333;
                        text-align: center;
                        font-family: Montserrat;
                        font-size: 16px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 20px;
                        text-transform: uppercase;
                        margin-bottom: 20px;
                    }

                    .process-cards_card-description p {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 15px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 22px;
                    }
                }
            }
        }
    }
}

@media (min-width: 567px) and (max-width: 777px) {
    .wrapper {
        display: flex;
        width: 100%;
        justify-content: center;
        // align-items: center;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap row;
            width: 90%;
            margin-top: 100px;
            .page_title {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;

                h1 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-top: 0px;
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

            .process-cards {
                display: flex;
                flex-flow: wrap row;
                width: 100%;
                .proces-cards_item {
                    height: 368px;
                    width: calc(50% - 12px);
                    display: flex;
                    justify-content: space-between;
                    flex-direction: column;
                    margin: 0 auto 40px;
                    .proces-cards_item-img {
                        margin-top: 0 !important;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        width: 95%;
                        margin: auto;
                        height: 219px;
                        background: #f5f5f5;
                        margin-bottom: 38px;
                        img {
                            transition: all 0.3s linear;
                        }
                        &:hover img {
                            transform: scale(1.1);
                        }
                    }

                    .process-cards_card-title h2 {
                        color: #333;
                        text-align: center;
                        font-family: Montserrat;
                        font-size: 16px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 20px;
                        text-transform: uppercase;
                        margin-bottom: 20px;
                    }

                    .process-cards_card-description p {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 15px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 22px;
                    }
                }
            }
        }
    }
}

@media (min-width: 777px) and (max-width: 992px) {
    .wrapper {
        display: flex;
        width: 100%;
        justify-content: center;
        // align-items: center;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap row;
            width: 90%;
            margin-top: 100px;
            .page_title {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;

                h1 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-top: 0px;
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

            .process-cards {
                display: flex;
                flex-flow: wrap row;
                width: 100%;
                .proces-cards_item {
                    height: 368px;
                    width: calc(33% - 12px);
                    display: flex;
                    justify-content: space-between;
                    flex-direction: column;
                    margin: 0 auto 40px;
                    .proces-cards_item-img {
                        margin-top: 0 !important;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        width: 95%;
                        margin: auto;
                        height: 219px;
                        background: #f5f5f5;
                        margin-bottom: 38px;
                        img {
                            transition: all 0.3s linear;
                        }
                        &:hover img {
                            transform: scale(1.1);
                        }
                    }

                    .process-cards_card-title h2 {
                        color: #333;
                        text-align: center;
                        font-family: Montserrat;
                        font-size: 16px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 20px;
                        text-transform: uppercase;
                        margin-bottom: 20px;
                    }

                    .process-cards_card-description p {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 15px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 22px;
                    }
                }
            }
        }
    }
}

@media (min-width: 992px) {
    .wrapper {
        display: flex;
        width: 100%;
        justify-content: center;
        // align-items: center;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap row;
            width: 65%;
            margin-top: 100px;
            .page_title {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;

                h1 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-top: 0px;
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

            .process-cards {
                display: flex;
                flex-flow: wrap row;
                width: 100%;
                .proces-cards_item {
                    height: 368px;
                    width: calc(33% - 12px);
                    display: flex;
                    justify-content: space-between;
                    flex-direction: column;
                    margin: 0 auto 40px;
                    .proces-cards_item-img {
                        margin-top: 0 !important;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        width: 95%;
                        margin: auto;
                        height: 219px;
                        background: #f5f5f5;
                        margin-bottom: 38px;
                        img {
                            transition: all 0.3s linear;
                        }
                        &:hover img {
                            transform: scale(1.1);
                        }
                    }

                    .process-cards_card-title h2 {
                        color: #333;
                        text-align: center;
                        font-family: Montserrat;
                        font-size: 16px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 20px;
                        text-transform: uppercase;
                        margin-bottom: 20px;
                    }

                    .process-cards_card-description p {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 15px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 22px;
                    }
                }
            }
        }
    }
}
</style>
