<template>
    <div class="wrapper">
        <div class="container">
            <div class="header">
                <h2>our team</h2>
                <div class="rectangle"></div>
            </div>
            <div class="members">
                <div class="member">
                    <img src="" alt="" />
                    <h3 class="member-name">Ron Swanson</h3>
                    <p class="member-role">Founder</p>
                    <div class="links"></div>
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
        height: 616px;
        .container {
            width: 90%;
            background-color: red;
            padding: 79px 0 0;
            margin-bottom: 28px;
            .header {
                display: flex;
                flex-flow: wrap column;
                justify-content: center;
                align-items: center;
                h2 {
                    color: #333;
                    text-align: center;
                    font-family: Montserrat;
                    font-size: 23px;
                    font-style: normal;
                    font-weight: 400;
                    line-height: 36px;
                    text-transform: uppercase;
                }
                .rectangle {
                    width: 80px;
                    height: 2px;
                    flex-shrink: 0;
                    background: rgba(0, 0, 0, 0.09);
                    margin-top: 28px 0 43px;
                }
            }
        }
    }
}
</style>
