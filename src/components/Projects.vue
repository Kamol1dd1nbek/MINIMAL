<template>
    <div class="wrapper">
        <div class="container">
            <div class="projects_head">
                <h2>Recent projects</h2>
                <div class="rectangle"></div>
            </div>
            <div class="projects_body">
                <div class="card">
                    <img
                        src="../assets/row1.1.jpg"
                        alt="image1.1"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>woods</h2>
                        <p>Photography</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row1.2.jpg"
                        alt="image1.2"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>path</h2>
                        <p>Website • Photography</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row1.3.jpg"
                        alt="image1.3"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>darkness</h2>
                        <p>Website</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row2.1.jpg"
                        alt="image2.1"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>waves</h2>
                        <p>Photography</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row2.2.jpg"
                        alt="image2.2"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>drops</h2>
                        <p>Website</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row2.3.jpg"
                        alt="image2.3"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>ocean</h2>
                        <p>Website</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row3.1.jpg"
                        alt="image3.1"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>town</h2>
                        <p>Website</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row3.2.jpg"
                        alt="image3.2"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>mountain</h2>
                        <p>Website</p>
                    </div>
                </div>
                <div class="card">
                    <img
                        src="../assets/row3.3.jpg"
                        alt="image3.3"
                        class="card-img"
                    />
                    <div class="card-body">
                        <h2>camera</h2>
                        <p>Website</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@media screen and (max-width: 567px) {
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        background: #f5f5f5;
        padding-top: 69px;
        margin-top: 74px;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: 90%;
            .projects_head {
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: column;
                width: 80%;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                }
                .rectangle {
                    margin: 28px 0 43px 0;
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .projects_body {
        display: flex;
        flex-direction: column;
        width: 85%;
        .card {
            display: flex;
            flex-direction: column;
            width: 95%;
            margin: 0 auto 30px;
            img {
                width: 100%;
            }
            .card-body {
                margin: 0;
                width: 100%;
                background-color: #fff;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 16px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px; /* 125% */
                    text-transform: uppercase;
                    margin-top: 19px;
                }
                p {
                    color: #333;
                    text-align: center;
                    font-family: Vollkorn;
                    font-size: 14px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px;
                    margin: 4px 0 21px 0;
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
        background: #f5f5f5;
        padding: 69px 0 89px;
        margin-top: 74px;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: 90%;
            .projects_head {
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: column;
                width: 80%;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                }
                .rectangle {
                    margin: 28px 0 43px 0;
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .projects_body {
        display: flex;
        flex-flow: wrap row;
        width: 90%;
        .card {
            display: flex;
            flex-direction: column;
            width: calc(50% - 20px);
            margin: 0 auto 30px;
            img {
                width: 100%;
            }
            .card-body {
                margin: 0;
                width: 100%;
                background-color: #fff;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 16px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px; /* 125% */
                    text-transform: uppercase;
                    margin-top: 19px;
                }
                p {
                    color: #333;
                    text-align: center;
                    font-family: Vollkorn;
                    font-size: 14px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px;
                    margin: 4px 0 21px 0;
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
        background: #f5f5f5;
        padding: 69px 0 89px;
        margin-top: 74px;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: 90%;
            .projects_head {
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: column;
                width: 80%;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                }
                .rectangle {
                    margin: 28px 0 43px 0;
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .projects_body {
        display: flex;
        flex-flow: wrap row;
        width: 90%;
        .card {
            display: flex;
            flex-direction: column;
            width: calc(33% - 10px);
            margin: 0 auto 30px;
            img {
                width: 100%;
            }
            .card-body {
                margin: 0;
                width: 100%;
                background-color: #fff;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 16px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px; /* 125% */
                    text-transform: uppercase;
                    margin-top: 19px;
                }
                p {
                    color: #333;
                    text-align: center;
                    font-family: Vollkorn;
                    font-size: 14px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px;
                    margin: 4px 0 21px 0;
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
        background: #f5f5f5;
        padding: 69px 0 89px;
        margin-top: 74px;
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: wrap column;
            width: 90%;
            .projects_head {
                display: flex;
                align-items: center;
                justify-content: center;
                flex-direction: column;
                width: 80%;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px; /* 156.522% */
                    text-transform: uppercase;
                }
                .rectangle {
                    margin: 28px 0 43px 0;
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                }
            }
        }
    }

    .projects_body {
        display: flex;
        flex-flow: wrap row;
        width: 70%;
        .card {
            display: flex;
            flex-direction: column;
            width: calc(33% - 10px);
            margin: 0 auto 30px;
            img {
                width: 100%;
            }
            .card-body {
                margin: 0;
                width: 100%;
                background-color: #fff;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 16px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px; /* 125% */
                    text-transform: uppercase;
                    margin-top: 19px;
                }
                p {
                    color: #333;
                    text-align: center;
                    font-family: Vollkorn;
                    font-size: 14px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 20px;
                    margin: 4px 0 21px 0;
                }
            }
        }
    }
}
</style>