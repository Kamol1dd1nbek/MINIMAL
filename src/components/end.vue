<template>
    <div class="wrapper d-flex justify-content-center align-items-center">
        <div class="container">
            <form>
                <input type="text" placeholder="Name" class="input-dark" />
                <input type="text" placeholder="Email" class="input-nodark" />
                <input type="text" placeholder="Budget" class="input-dark" />
                <textarea
                    name=""
                    id=""
                    rows="3"
                    placeholder="Describe youre project..."
                    class="input-nodark"
                >
Describe youre project...</textarea
                >
                <button type="submit">Send Message</button>
            </form>
            <div class="footer">
                <img src="../assets/IMAGE.png" alt="logo" />
                <h4>Minimal Template made in Webflow. All rights reserved.</h4>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Vollkorn&display=swap");

@media (max-width: 600px) {
    .wrapper {
        display: flex;
        height: 639px;
        justify-content: center;
        padding: 69px 0;
        width: 100%;
        background-color: #000;
        .container {
            display: flex;
            width: 100%;
            flex-direction: column;
            align-items: center;
            gap: 15.047px;
        }
        form {
            width: 94% !important;
            display: flex;
            flex-flow: nowrap column;
            input {
                height: 57px;
                width: 100%;
                flex-shrink: 0;
                outline: none;
                border: none;
                color: #fff;
                text-align: left;
                font-family: Vollkorn;
                font-size: 16px;
                font-style: italic;
                font-weight: 400;
                line-height: 22px;
                padding: 18px 0 17px 31px;
                &::placeholder {
                    padding-right: 10px;
                    float: left;
                    color: #fff;
                    text-align: left;
                    font-family: Vollkorn;
                    font-size: 16px;
                    font-style: italic;
                    font-weight: 400;
                    line-height: 22px;
                }
            }
            textarea {
                resize: none;
                width: 100%;
                height: 127px;
                flex-shrink: 0;
                outline: none;
                border: none;
                color: #fff;
                text-align: left;
                font-family: Vollkorn;
                font-size: 17px;
                font-style: italic;
                font-weight: 400;
                line-height: 22px;
                padding: 17px 0 0 31px;
                float: left;
            }
            button {
                width: 210px;
                height: 53px;
                color: #8bcac3;
                text-align: center;
                font-family: Vollkorn;
                font-size: 17px;
                font-style: italic;
                font-weight: 400;
                line-height: 22px;
                margin: 22px auto;
                border-bottom: 2px solid #7ec4bd;
                border-top: 1px solid #7ec4bd;
                border-left: 1px solid #7ec4bd;
                border-right: 1px solid #7ec4bd;
                background: transparent;
            }
        }
    }
    form {
        .input-dark {
            background: rgba(255, 255, 255, 0.18);
        }
        .input-nodark {
            background: rgba(255, 255, 255, 0.2);
        }
    }

    .footer {
        img {
            margin: 15px 0;
        }
        h4 {
            color: rgba(255, 255, 255, 0.4);
            text-align: center;
            font-family: Vollkorn;
            font-size: 15px;
            font-style: normal;
            font-weight: 400;
            line-height: 22px; /* 146.667% */
        }
    }
}
@media (min-width: 601px) and (max-width: 1084px) {
    .wrapper {
    display: flex;
    height: 639px;
    width: 100% !important;
    justify-content: center;
    padding: 69px 0;
    background-color: #000;
    .container {
        display: flex;
        width: 80%;
        flex-direction: column;
        align-items: center;
        // gap: 15.047px;
    }
    form {
        width: 100%;
        display: flex;
        flex-flow: nowrap column;
        input {
            width: 100%;
            height: 57px;
            flex-shrink: 0;
            outline: none;
            border: none;
            color: #fff;
            text-align: left;
            font-family: Vollkorn;
            font-size: 16px;
            font-style: italic;
            font-weight: 400;
            line-height: 22px;
            padding: 18px 0 17px 31px;
            &::placeholder {
                padding-right: 10px;
                float: left;
                color: #fff;
                text-align: left;
                font-family: Vollkorn;
                font-size: 16px;
                font-style: italic;
                font-weight: 400;
                line-height: 22px;
            }
        }
        textarea {
            resize: none;
            width: 100%;
            height: 127px;
            flex-shrink: 0;
            outline: none;
            border: none;
            color: #fff;
            text-align: left;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: italic;
            font-weight: 400;
            line-height: 22px;
            padding: 17px 0 0 31px;
            float: left;
        }
        button {
            width: 210px;
            height: 53px;
            color: #8bcac3;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: italic;
            font-weight: 400;
            line-height: 22px;
            margin: 22px auto;
            border-bottom: 2px solid #7ec4bd;
            border-top: 1px solid #7ec4bd;
            border-left: 1px solid #7ec4bd;
            border-right: 1px solid #7ec4bd;
            background: transparent;
        }
    }
}
form {
    .input-dark {
        background: rgba(255, 255, 255, 0.18);
    }
    .input-nodark {
        background: rgba(255, 255, 255, 0.2);
    }
}
.footer {
    img {
        margin: 15px 0;
    }
    h4 {
        color: rgba(255, 255, 255, 0.4);
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 146.667% */
    }
}
}
@media (min-width: 1084px) {
    .wrapper {
    display: flex;
    height: 639px;
    width: 100% !important;
    justify-content: center;
    padding: 69px 0;
    background-color: #000;
    .container {
        display: flex;
        width: 55%;
        flex-direction: column;
        align-items: center;
        // gap: 15.047px;
    }
    form {
        width: 100%;
        display: flex;
        flex-flow: nowrap column;
        input {
            width: 100%;
            height: 57px;
            flex-shrink: 0;
            outline: none;
            border: none;
            color: #fff;
            text-align: left;
            font-family: Vollkorn;
            font-size: 16px;
            font-style: italic;
            font-weight: 400;
            line-height: 22px;
            padding: 18px 0 17px 31px;
            &::placeholder {
                padding-right: 10px;
                float: left;
                color: #fff;
                text-align: left;
                font-family: Vollkorn;
                font-size: 16px;
                font-style: italic;
                font-weight: 400;
                line-height: 22px;
            }
        }
        textarea {
            resize: none;
            width: 100%;
            height: 127px;
            flex-shrink: 0;
            outline: none;
            border: none;
            color: #fff;
            text-align: left;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: italic;
            font-weight: 400;
            line-height: 22px;
            padding: 17px 0 0 31px;
            float: left;
        }
        button {
            width: 210px;
            height: 53px;
            color: #8bcac3;
            text-align: center;
            font-family: Vollkorn;
            font-size: 17px;
            font-style: italic;
            font-weight: 400;
            line-height: 22px;
            margin: 22px auto;
            border-bottom: 2px solid #7ec4bd;
            border-top: 1px solid #7ec4bd;
            border-left: 1px solid #7ec4bd;
            border-right: 1px solid #7ec4bd;
            background: transparent;
        }
    }
}
form {
    .input-dark {
        background: rgba(255, 255, 255, 0.18);
    }
    .input-nodark {
        background: rgba(255, 255, 255, 0.2);
    }
}
.footer {
    img {
        margin: 15px 0;
    }
    h4 {
        color: rgba(255, 255, 255, 0.4);
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 146.667% */
    }
}
}

</style>
