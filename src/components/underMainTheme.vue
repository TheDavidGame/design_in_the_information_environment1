<template>
    <div class="underMain__wrapper">
        <div class="underMain__upperPhoto">
            <img src="../static/underMain_upperPhoto-item.svg" alt="underMain_upperPhoto-item"
                class="underMain__upperPhoto-item" />
            <div class="underMain__upperPhoto-text-first">
                Reeding House
            </div>
            <div class="underMain__upperPhoto-text-second">
                Lorem ipsum dolor sit amet, dolor sit amet dolor sit amet.
            </div>
        </div>
        <div class="underMain__main">
            <div class="underMain__main-title">
                <div class="underMain__main-title-upper">Our process</div>
                <div class="underMain__main-title-under">How we do what we do.</div>
            </div>
            <div class="underMain__main-list">
                <div class="underMain__main-item">
                    <div class="underMain__main-item-photo">
                        <img src="../static/Sketching.svg" alt="underMain_main-item-photo-Sketching"
                            class="underMain__main-item-photo-Sketching" />
                    </div>
                    <div class="underMain__main-item-title">Sketching</div>
                    <div class="underMain__main-item-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ut
                        tristique libero. Nulla luctus sapien ac arcu tempor, vitae tempor leo iaculis.</div>
                </div>
                <div class="underMain__main-item">
                    <div class="underMain__main-item-photo">
                        <img src="../static/Finalizing.svg" alt="underMain_main-item-photo-Finalizing"
                            class="underMain__main-item-photo-Finalizing" />
                    </div>
                    <div class="underMain__main-item-title">Finalizing</div>
                    <div class="underMain__main-item-text">Adipiscing elit. Nulla ut tristique libero. Nulla vitae tempor
                        leo iaculis luctus sapien ac arcu tempor, vitae.</div>
                </div>
                <div class="underMain__main-item">
                    <div class="underMain__main-item-photo">
                        <img src="../static/Building.svg" alt="underMain_main-item-photo-Building"
                            class="underMain__main-item-photo-Building" />
                    </div>
                    <div class="underMain__main-item-title">Building</div>
                    <div class="underMain__main-item-text">Nulla ut tristique libero. Lorem ipsum ut tristique libero. Nulla
                        luctus sapien ac arcu tempor, vitae lorem ipsum dolor leo iaculis.</div>
                </div>
            </div>
        </div>
        <div class="underMain__underPhoto">
            <img src="../static/underMain_underPhoto-item.svg" alt="underMain_underPhoto-item"
                class="underMain__underPhoto-item" />
            <div class="underMain__underPhoto-text-first">
                The swirling staircase
            </div>
            <div class="underMain__underPhoto-text-second">
                Lorem ipsum dolor sit amet, dolor sit amet dolor sit amet.
            </div>
        </div>
    </div>
</template>
  
<script>

import "@fontsource/poppins";

export default {
    name: 'underMainTheme',
}
</script>
  
<style>
.underMain__wrapper {
    width: 100%;
}

.underMain__upperPhoto {
    position: relative;
}

.underMain__upperPhoto-item {
    height: 632px;
    width: auto;
}

.underMain__upperPhoto-text-first {
    position: absolute;
    top: 40%;
    left: 80%;
    transform: translate(-50%, -50%);
    color: #403E3B;

    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    text-transform: uppercase;
}

.underMain__upperPhoto-text-second {
    position: absolute;
    top: 45%;
    left: 84.38%;
    transform: translate(-50%, -50%);
    color: #645C55;

    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
}

.underMain__main {
    margin-top: 100px;
}

.underMain__main-title-upper {
    color: #645C55;

    text-align: center;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    text-transform: uppercase;
}

.underMain__main-title-under {
    color: #1B1A1A;

    text-align: center;
    font-family: Poppins;
    font-size: 39px;
    font-style: normal;
    font-weight: 400;
    line-height: 42px;
}

.underMain__main-list {
    margin-top: 40px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
}

.underMain__main-item {
    margin-bottom: 110px;
}

.underMain__main-item-title {
    margin: 15px 0 5px 0;

    color: #403E3B;
    text-align: center;
    font-family: Poppins;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 26px;
}

.underMain__main-item-photo {
    display: flex;
    justify-content: center;
}

.underMain__main-item-text {
    width: 294px;
    height: 96px;
    color: #645C55;
    text-align: center;
    font-family: Poppins;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
}

.underMain__underPhoto {
    position: relative;
}

.underMain__underPhoto-item {
    height: 632px;
}

.underMain__underPhoto-text-first {
    position: absolute;
    top: 50%;
    left: 10.38%;
    transform: translate(-50%, -50%);
    color: #403E3B;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

.underMain__underPhoto-text-second {
    position: absolute;
    top: 55%;
    left: 12.80%;
    transform: translate(-50%, -50%);
    color: #645C55;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    width: 285px;
}

@media screen and (max-width: 376px) {
    .underMain__upperPhoto-item {
        height: 312px;
        width: 375px;
        object-fit: cover;
    }

    .underMain__upperPhoto-text-first {
        font-size: 14px;
        line-height: 20px;
        width: 210px;
        transform: translate(-65%, 80%);
        top: 60%;
    }

    .underMain__upperPhoto-text-second {
        top: 54%;
        left: 88.38%;
        line-height: 14px;
        transform: translate(-80%, 85%);
        width: 210px;
        font-size: 16px;
        line-height: 24px;
    }

    .underMain__underPhoto-item {
        width: 375px;
        height: 312px;
        object-fit: cover;
    }

    .underMain__underPhoto-text-first {
        top: 18%;
        left: 15.60%;
        transform: translate(-20%, -100%);
        font-size: 14px;
        line-height: 20px;
        width: 223px;
    }

    .underMain__underPhoto-text-second {
        top: 30%;
        left: 33.60%;
        font-size: 16px;
        line-height: 24px;
        width: 223px;
    }

    .underMain__main-title-under {
        line-height: 140%;
        font-size: 24px;
    }

    .underMain__main-item-photo {
        height: 84px;
    }


}
</style>
  