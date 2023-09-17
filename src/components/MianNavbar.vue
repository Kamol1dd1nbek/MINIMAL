<template>
    <div class="wrapper">
        <nav>
            <div class="navbar_logo">
                <img :src="Logo" alt="logo" />
                <h2>minimal</h2>
            </div>
            <ul class="navbar_links">
                <li>process</li>
                <li>projects</li>
                <li>team</li>
                <li>contact</li>
            </ul>
        </nav>
    </div>
</template>

<script setup>
import Logo from "../assets/navbarLogo.png";
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&display=swap");
.wrapper {
    background-color: #fff;
}
.wrapper {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 10px;
    padding-bottom: 0 !important;
    nav {
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 72%;
        .navbar_logo {
            display: flex;
            align-items: center;
            gap: 18px;
        }

        .navbar_links {
            display: flex;
            align-items: center;
            justify-content: center;
            li {
                list-style: none;
                margin: 0 34px;
                color: #404040;
                font-family: Montserrat;
                font-size: 12px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                cursor: pointer;
            }
        }
    }
}
.navbar_logo {
    img {
        width: 65px;
        height: 70px;
        flex-shrink: 0;
    }

    h2 {
        color: #333;
        font-family: Oswald;
        font-size: 22px;
        font-style: normal;
        font-weight: 400;
        line-height: 38px;
        text-transform: uppercase;
    }
}

@media screen and (max-width: 827px) {
    nav {
        display: flex;
        align-content: center;
        justify-content: center;
        gap: 20px;
        flex-flow: wrap column;
        width: 95% !important;
        .navbar_logo {
            display: flex;
            align-items: center;
            gap: 20px;
            margin: 10px;
        }

        .navbar_links {
            display: flex;
            align-items: center;
            justify-content: space-around !important;
            width: 100%;
            li {
                margin: 0 !important;
                list-style: disc;
                color: #404040;
                font-family: Montserrat;
                font-size: 12px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                cursor: pointer;
            }
        }
    }
    .navbar_logo {
        img {
            width: 60px;
            height: 65px;
            flex-shrink: 0;
        }

        h2 {
            color: #333;
            font-family: Oswald;
            font-size: 20px;
            font-style: normal;
            font-weight: 400;
            line-height: 38px;
            text-transform: uppercase;
        }
    }
}

@media screen and (max-width: 300px) {
    nav {
        position: relative;
        display: flex;
        align-content: center;
        justify-content: center;
        // gap: 20px;
        flex-flow: wrap row;
        width: 100% !important;
        .navbar_logo {
            display: flex;
            align-items: center;
            gap: 20px;
            margin: 10px;
        }

        .navbar_links {
            visibility: hidden;
            display: flex;
            align-items: center;
            justify-content: space-around !important;
            width: 100%;
            li {
                margin: 0 !important;
                list-style: disc;
                color: #404040;
                font-family: Montserrat;
                font-size: 12px;
                font-style: normal;
                font-weight: 400;
                line-height: 20px;
                text-transform: uppercase;
                cursor: pointer;
                background-color: #fff;
            }

            &::after {
                position: absolute;
                right: -8px;
                padding-right: 10px;
                top: 20px;
                content: "|||";
                visibility: visible;
                color: #000;
                font-size: 24px;
                font-weight: 900;
                transform: rotate(90deg);
                background-color: #fff;
            }
        }
    }
    .navbar_logo {
        img {
            width: 40px;
            height: 45px;
            flex-shrink: 0;
        }

        h2 {
            color: #333;
            font-family: Oswald;
            font-size: 17px;
            font-style: normal;
            font-weight: 400;
            line-height: 38px;
            text-transform: uppercase;
        }
    }
}

</style>