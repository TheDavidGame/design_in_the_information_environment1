<template>
    <div class="upperFooter__wrapper">
        <div class="upperFooter__top">
            <div class="upperFooter__mainText">
                <div class="upperFooter__mainText-top">
                    <p class="upperFooter__mainText-top-item">
                        Featured projects
                    </p>
                </div>
                <div class="upperFooter__mainText-bottom">
                    <p class="upperFooter__mainText-bottom-item">
                        Some of the latest and greatest projects from us here at Wishbone+Partners.
                    </p>
                </div>
            </div>
            <div class="upperFooter__photoList">
                <div class="upperFooter__photoList-item">
                    <img src="../static/upperFooter__photoList-item-left.svg" alt="upperFooter__photoList-item-photo"
                        class="upperFooter__photoList-item-photo" />
                </div>
                <div class="upperFooter__photoList-item">
                    <img src="../static/upperFooter__photoList-item-middle.svg" alt="upperFooter__photoList-item-photo"
                        class="upperFooter__photoList-item-photo" />
                </div>
                <div class="upperFooter__photoList-item">
                    <img src="../static/upperFooter__photoList-item-right.svg" alt="upperFooter__photoList-item-photo"
                        class="upperFooter__photoList-item-photo" />
                </div>
            </div>
            <div class="upperFooter__secText">
                <p class="upperFooter__secText-item">
                    View all projects
                </p>
            </div>
        </div>
        <div class="upperFooter__bottom">
            <div class="upperFooter__left">
                <div class="upperFooter__left-upperMain">Meet our team</div>
                <div class="upperFooter__left-middleMain">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis.</div>
                <div class="upperFooter__left-underMain">See team</div>
            </div>
            <div class="upperFooter__right">
                <div class="upperFooter__list">
                    <div class="upperFooter__list-item">
                        <div class="upperFooter__list-item-photo">
                            <img src="../static/Stephen_Collier.svg" alt="upperFooter__list-item-photo"
                                class="upperFooter__list-item-photo" />
                        </div>
                        <div class="upperFooter__list-item-text">
                            <div class="upperFooter__list-item-text-name">Stephen Collier</div>
                            <div class="upperFooter__list-item-text-description">Senior Partner</div>
                        </div>

                    </div>
                    <div class="upperFooter__list-item">
                        <div class="upperFooter__list-item-photo">
                            <img src="../static/Ferris_Wonder.svg" alt="upperFooter__list-item-photo"
                                class="upperFooter__list-item-photo" />
                        </div>
                        <div class="upperFooter__list-item-text">
                            <div class="upperFooter__list-item-text-name">Ferris Wonder</div>
                            <div class="upperFooter__list-item-text-description">Associate Partner</div>
                        </div>

                    </div>
                    <div class="upperFooter__list-item">
                        <div class="upperFooter__list-item-photo">
                            <img src="../static/Niko_Ferry.svg" alt="upperFooter__list-item-photo"
                                class="upperFooter__list-item-photo" />
                        </div>
                        <div class="upperFooter__list-item-text">
                            <div class="upperFooter__list-item-text-name">Niko Ferry</div>
                            <div class="upperFooter__list-item-text-description">Partner</div>
                        </div>

                    </div>
                    <div class="upperFooter__list-item">
                        <div class="upperFooter__list-item-photo">
                            <img src="../static/Nolan_Peters.svg" alt="upperFooter__list-item-photo"
                                class="upperFooter__list-item-photo" />
                        </div>
                        <div class="upperFooter__list-item-text">
                            <div class="upperFooter__list-item-text-name">Nolan Peters</div>
                            <div class="upperFooter__list-item-text-description">Associate</div>
                        </div>

                    </div>
                    <div class="upperFooter__list-item">
                        <div class="upperFooter__list-item-photo">
                            <img src="../static/Aria_Stone.svg" alt="upperFooter__list-item-photo"
                                class="upperFooter__list-item-photo" />
                        </div>
                        <div class="upperFooter__list-item-text">
                            <div class="upperFooter__list-item-text-name">Aria Stone</div>
                            <div class="upperFooter__list-item-text-description">Senior Partner</div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>

import "@fontsource/poppins";

export default {
    name: 'upperFooter',
}
</script>
  
<style>
.upperFooter__top {
    padding: 120px 120px 100px 120px;
    background: #F7F7F7;
    margin-top: -7px;
}

.upperFooter__mainText-top-item {
    color: #1B1A1A;
    font-family: Poppins;
    font-size: 39px;
    font-style: normal;
    font-weight: 400;
    line-height: 42px;
    padding-bottom: 15px;
}

.upperFooter__mainText-bottom-item {
    color: #645C55;
    font-family: Poppins;
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: 30px;
    padding-bottom: 42px;
}

.upperFooter__photoList {
    display: flex;
}

.upperFooter__photoList-item {
    margin-right: 20px;
}

.upperFooter__secText-item {
    color: #1B1A1A;
    text-align: center;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    letter-spacing: 0.4px;
    padding-top: 50px;
}

.upperFooter__bottom {
    display: flex;
    justify-content: space-between;
    margin: 100px 136px 100px 136px;
}

.upperFooter__left-upperMain {
    color: #403E3B;
    font-family: Poppins;
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 38px;
}

.upperFooter__left-middleMain {
    margin: 14px 0 41px 0;
    color: #645C55;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    width: 358px;
}

.upperFooter__left-underMain {
    margin-left: 20px;
    color: #1B1A1A;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    letter-spacing: 0.4px;
}

.upperFooter__list {
    width: 770px;
    height: 390px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
}

.upperFooter__list-item {
    display: flex;
    margin-bottom: 36px;
}

.upperFooter__list-item-text {
    margin-left: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.upperFooter__list-item-text-name {
    color: #1B1A1A;
    font-family: Poppins;
    font-size: 17px;
    font-style: normal;
    font-weight: 400;
    line-height: 26px;
}

.upperFooter__list-item-text-description {
    color: #645C55;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 14px;
}

@media screen and (max-width: 376px) {
    .upperFooter__bottom {
        flex-direction: column;
        flex-wrap: wrap;
        margin: 56px 136px 246px 5px;
    }

    .upperFooter__left {
        width: 375px;
    }

    .upperFooter__right {
        width: 375px;
    }

    .upperFooter__left-underMain {
        margin: 0 0 10px 2px;
    }

    .upperFooter__list {
        width: 370px;
        height: 390px;
        display: flex;
        flex-direction: column;
        flex-wrap: nowrap;
    }

    .upperFooter__top {
        padding: 51px 12px 10px 19px;
    }

    .upperFooter__mainText-top-item {
        color: #1B1A1A;
        font-size: 24px;
        line-height: 140%;
        margin-bottom: -20px;
    }

    .upperFooter__mainText-bottom-item {
        font-size: 16px;
        line-height: 140%;
        width: 343px;
    }

    .upperFooter__photoList {
        flex-direction: column;
    }

    .upperFooter__photoList-item-photo {
        width: 344px;
        height: 458px;
        object-fit: cover;
    }

    .upperFooter__secText-item {
        padding-top: 0px;
    }

    .upperFooter__left-upperMain {
        line-height: 140%;
        font-size: 24px;
    }
}
</style>