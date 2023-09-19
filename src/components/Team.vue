<template>
    <div class="wrapper">
        <div class="container">
            <div class="header">
                <h2>our team</h2>
                <div class="rectangle"></div>
            </div>
            <div class="members">
                <div class="member">
                    <img src="../assets/team-1.jpg" alt="" class="user_photo" />
                    <h3 class="member-name">Ron Swanson</h3>
                    <p class="member-role">Founder</p>
                    <div class="links">
                        <div class="link-container">
                            <img src="../assets/twitter.png" alt="" />
                            <img src="../assets/in.png" alt="" />
                            <img src="../assets/message.png" alt="" />
                        </div>
                    </div>
                </div>
                <div class="member">
                    <img src="../assets/team-2.jpg" alt="" class="user_photo" />
                    <h3 class="member-name">Julia Depish</h3>
                    <p class="member-role">Marketing</p>
                    <div class="links">
                        <div class="link-container">
                            <img src="../assets/twitter.png" alt="" />
                            <img src="../assets/in.png" alt="" />
                            <img src="../assets/message.png" alt="" />
                        </div>
                    </div>
                </div>
                <div class="member">
                    <img src="../assets/team-3.jpg" alt="" class="user_photo" />
                    <h3 class="member-name">Danny Devry</h3>
                    <p class="member-role">Designer</p>
                    <div class="links">
                        <div class="link-container">
                            <img src="../assets/instagram.png" alt="" />
                            <img src="../assets/twitter.png" alt="" />
                            <img src="../assets/be.png" alt="" />
                            <img src="../assets/internet.png" alt="" />
                            <img src="../assets/message.png" alt="" />
                        </div>
                    </div>
                </div>
                <div class="member">
                    <img src="../assets/team-4.jpg" alt="" class="user_photo" />
                    <h3 class="member-name">Lisa Smith</h3>
                    <p class="member-role">Developer</p>
                    <div class="links">
                        <div class="link-container">
                            <img src="../assets/facebook.png" alt="" />
                            <img src="../assets/twitter.png" alt="" />
                            <img src="../assets/message.png" alt="" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Vollkorn&display=swap");
@media screen and (max-width: 567px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        // height: 616px;
        margin-top: 35px;
        .container {
            padding-top: 10px;
            width: 90%;
            margin-bottom: 28px;

            .header {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;
                margin-bottom: 43px;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .members {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-flow: wrap column;
        margin-top: 30px;
        gap: 30px;
        .member {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: 85%;
            .user_photo {
                width: 90%;
            }
            h3 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                margin: 20px 0 6px;
            }
            p {
                color: #333;
                text-align: center;
                font-family: Vollkorn;
                font-size: 14px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                margin-bottom: 5px;
            }
            .links {
                width: 90%;
                height: 35px;
                display: flex;
                justify-content: center;
                align-items: center;
                .link-container {
                    background-color: #fff;
                    width: 50%;
                    height: 100%;
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    overflow: hidden;
                }
            } 
        }
    }
}
@media screen and (min-width: 567px) and (max-width: 777px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        margin-top: 35px;
        .container {
            padding-top: 10px;
            width: 90%;
            margin-bottom: 28px;

            .header {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;
                margin-bottom: 43px;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .members {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-flow: wrap row;
        margin-top: 30px;
        gap: 30px;
        .member {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: calc(50% - 40px);
            .user_photo {
                width: 90%;
            }
            h3 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                margin: 20px 0 6px;
            }
            p {
                color: #333;
                text-align: center;
                font-family: Vollkorn;
                font-size: 14px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                margin-bottom: 5px;
            }
            .links {
                width: 90%;
                height: 35px;
                display: flex;
                justify-content: center;
                align-items: center;
                .link-container {
                    background-color: #fff;
                    width: 50%;
                    height: 100%;
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    overflow: hidden;
                }
            } 
        }
    }
}
@media (min-width: 777px) and (max-width: 992px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        margin-top: 35px;
        .container {
            padding-top: 10px;
            width: 90%;
            margin-bottom: 28px;

            .header {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;
                margin-bottom: 43px;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .members {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-flow: wrap row;
        margin-top: 30px;
        gap: 30px;
        .member {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: calc(33% - 40px);
            .user_photo {
                width: 90%;
            }
            h3 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                margin: 20px 0 6px;
            }
            p {
                color: #333;
                text-align: center;
                font-family: Vollkorn;
                font-size: 14px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                margin-bottom: 5px;
            }
            .links {
                width: 90%;
                height: 35px;
                display: flex;
                justify-content: center;
                align-items: center;
                .link-container {
                    background-color: #fff;
                    width: 50%;
                    height: 100%;
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    overflow: hidden;
                }
            } 
        }
    }
}
@media (min-width: 992px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        margin-top: 35px;
        .container {
            padding-top: 10px;
            width: 90%;
            margin-bottom: 28px;

            .header {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;
                margin-bottom: 43px;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                    margin-bottom: 28px;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .members {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-flow: wrap row;
        margin-top: 30px;
        gap: 30px;
        .member {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: calc(23% - 40px);
            .user_photo {
                width: 95%;
            }
            h3 {
                color: #333;
                text-align: center;
                font-family: Montserrat;
                font-size: 16px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                margin: 20px 0 6px;
            }
            p {
                color: #333;
                text-align: center;
                font-family: Vollkorn;
                font-size: 14px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                margin-bottom: 5px;
            }
            .links {
                width: 95%;
                height: 35px;
                display: flex;
                justify-content: center;
                align-items: center;
                .link-container {
                    background-color: #fff;
                    width: 50%;
                    height: 100%;
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    overflow: hidden;
                }
            } 
        }
    }
}
</style>
