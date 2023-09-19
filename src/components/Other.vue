<template>
    <div class="wrapper">
        <div class="container">
            <div class="header">
                <img src="../assets/tirnoq2.png" alt="quote" class="quote" />
            </div>
            <div class="body">
                <div class="body-item">
                    <h3>
                        “I love these guys! They did a great job. I would
                        recommend them to anyone.”
                    </h3>
                    <div class="body-bottom">
                        <img src="../assets/other1.jpg" alt="other" />
                        <p>Julius Von Uberstien</p>
                    </div>
                </div>
                <div class="body-item">
                    <h3>
                        “Elexis Corp. has grown immensely with the help of
                        Minimal.”
                    </h3>
                    <div class="body-bottom">
                        <img src="../assets/other1.jpg" alt="other" />
                        <p>Julius Von Uberstien</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Vollkorn&display=swap");
@media screen and (max-width: 425px) {
    .wrapper {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #f5f5f5;
        padding: 80px;
        .container {
            display: flex;
            width: 100%;
            justify-content: center;
            align-items: center;
            flex-flow: wrap column;
            .header {
                display: flex;
                justify-content: center;
                width: 100%;
                margin-bottom: 37px;
                img {
                    width: 50px;
                }
            }

            .body {
                display: flex;
                flex-flow: wrap column;
                gap: 30px;
                .body-item {
                    display: flex;
                    flex-flow: wrap column;
                    padding-bottom: 40px; 
                    h3 {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 19px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 25px;
                        margin-bottom: 24px;
                    }
                    .body-bottom {
                        p {
                            margin-top: 10px;
                            color: #ababab;
                            text-align: center;
                            font-family: Montserrat;
                            font-size: 14px;
                            font-style: normal;
                            font-weight: 400;
                            line-height: 20px;
                            text-transform: uppercase;
                        }
                    }
                }
            }
        }
    }
    .body .body-item:first-child {
        padding-bottom: 30px;
        border-bottom: 2px solid #ababab;
        margin-bottom: 10px;
    }
}
@media screen and (min-width: 425px) and (max-width: 777px) {
    .wrapper {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #f5f5f5;
        padding: 69px;
        .container {
            // padding: 0 24px;
            display: flex;
            width: 60%;
            justify-content: center;
            align-items: center;
            flex-flow: wrap column;
            .header {
                display: flex;
                justify-content: center;
                width: 100%;
                margin-bottom: 37px;
                img {
                    width: 50px;
                }
            }

            .body {
                display: flex;
                flex-flow: wrap column;
                gap: 30px;
                .body-item {
                    display: flex;
                    flex-flow: wrap column;
                    padding-bottom: 40px; 
                    h3 {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 23px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 25px;
                        margin-bottom: 24px;
                    }
                    .body-bottom {
                        p {
                            margin-top: 10px;
                            color: #ababab;
                            text-align: center;
                            font-family: Montserrat;
                            font-size: 14px;
                            font-style: normal;
                            font-weight: 400;
                            line-height: 20px;
                            text-transform: uppercase;
                        }
                    }
                }
            }
        }
    }
    .body .body-item:first-child {
        padding-bottom: 30px;
        border-bottom: 2px solid #ababab;
        margin-bottom: 10px;
    }
}
@media screen and (min-width: 777px) and (max-width: 1045px) {
    .wrapper {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #f5f5f5;
        padding: 69px 0;
        .container {
            display: flex;
            width: 100%;
            justify-content: center;
            align-items: center;
            flex-flow: wrap column;
            .header {
                display: flex;
                justify-content: center;
                width: 100%;
                margin-bottom: 37px;
                img {
                    width: 50px;
                }
            }

            .body {
                position: relative;
                width: 100%;
                display: flex;
                justify-content: center;
                flex-flow: wrap row;
                gap: 10px;
                .body-item {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    flex-flow: wrap column;
                    width: calc(50% - 40px);
                    padding: 0 !important;
                    h3 {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 18px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 25px;
                        margin-bottom: 24px;
                    }
                    .body-bottom {
                        margin-top: 40px;
                        // position: absolute;
                        // bottom: 0;
                        p {
                            margin-top: 10px;
                            color: #ababab;
                            text-align: center;
                            font-family: Montserrat;
                            font-size: 14px;
                            font-style: normal;
                            font-weight: 400;
                            line-height: 20px; /* 142.857% */
                            text-transform: uppercase;
                        }
                        img {
                            width: 64px;
                            height: 64px;
                            flex-shrink: 0;
                        }
                    }
                }
            }
        }
    }

    .body .body-item:first-child {
        padding-bottom: 30px;
        border-right: 2px solid #ababab;
        padding-right: 13px;
    }
}
@media screen and (min-width: 1046px) {
    .wrapper {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #f5f5f5;
        padding: 69px 0;
        .container {
            display: flex;
            width: 100%;
            justify-content: center;
            align-items: center;
            flex-flow: wrap column;
            .header {
                display: flex;
                justify-content: center;
                width: 100%;
                margin-bottom: 37px;
                img {
                    width: 50px;
                }
            }

            .body {
                position: relative;
                width: 940px;
                display: flex;
                justify-content: center;
                flex-flow: wrap row;
                gap: 10px;
                .body-item {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    flex-flow: wrap column;
                    width: calc(50% - 40px);
                    padding: 0 !important;
                    h3 {
                        color: #333;
                        text-align: center;
                        font-family: Vollkorn;
                        font-size: 18px;
                        font-style: normal;
                        font-weight: 400;
                        line-height: 25px;
                        margin-bottom: 24px;
                    }
                    .body-bottom {
                        margin-top: 40px;
                        // position: absolute;
                        // bottom: 0;
                        p {
                            margin-top: 10px;
                            color: #ababab;
                            text-align: center;
                            font-family: Montserrat;
                            font-size: 14px;
                            font-style: normal;
                            font-weight: 400;
                            line-height: 20px; /* 142.857% */
                            text-transform: uppercase;
                        }
                        img {
                            width: 64px;
                            height: 64px;
                            flex-shrink: 0;
                        }
                    }
                }
            }
        }
    }

    .body .body-item:first-child {
        padding-bottom: 30px;
        border-right: 2px solid #ababab;
        padding-right: 13px;
    }
}
</style>
