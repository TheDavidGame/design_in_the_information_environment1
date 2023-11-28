<template>
    <header class="header">
        <div class="header__wrapper">
            <div class="header__logo">
                <img href="#!" src="../static/logo.svg" alt="header_logo" class="header__logo" />
            </div>
            <nav class="header__nav">
                <ul class="header__list">
                    <li class="header__item">
                        <p class="header__item-text">
                            Projects
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            About
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            News
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            Team
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            Contact
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            Get template
                        </p>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>
  
<script>

import "@fontsource/poppins";

export default {
    name: 'headerMainTheme',
}
</script>
  
<style>
.header {
    width: 100%;
    height: 90px;
    z-index: 999;
}

.header__wrapper {
    display: flex;
    flex-wrap: wrap;
    align-items: first baseline;
    justify-content: space-between;
}

.header__logo {
    width: 220px;
    height: 19px;
    margin-left: 52px;
}

.header__list {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}

.header__item {
    list-style-type: none;
    margin-right: 32px;
}

.header__item:last-child {
    border-radius: 14px;
    background: #1B1A1A;
}

.header__item:last-child .header__item-text {
    color: #FFF;
    width: 155px;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 46px;
}

.header__item-text {
    color: #1B1A1A;

    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px
}

@media screen and (max-width: 376px) {
    .header {
        height: 130px;
    }

    .header__logo {
        margin: 0 auto;
        margin-top: 10px;
    }

    .header__item:last-child .header__item-text {
        width: 134px;
        height: 30px;
    }
}
</style>