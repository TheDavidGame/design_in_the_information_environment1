<template>
  <div class="main__wrapper">
    <div class="header__wrapper">
      <div class="header__left">
        <div class="header__title-upper">
          <p class="header__title-upper-text">WISHBONE+PARTNERS</p>
        </div>
        <div class="header__title">
          <p class="header__title-text">The home of beautiful architecture.</p>
        </div>
        <div class="header__footer">
          <p class="header__footer-text">We are an architecture firm with a focus on beautiful but functional design.
            At its heart, we believe design is about usability and accessibility — these are
            the guiding principles for our work. Read more about our previous projects,
            our process and our team below.</p>
          <p class="header__footer-text-lower">Read more</p>
        </div>
      </div>
      <div class="header__right">
        <div class="header__photo">
          <img src="../static/header_photo.svg" alt="header_photo" class="header__photo" />
        </div>
      </div>

    </div>
    <div class="footer__wrapper">
      <div class="footer__wrapper-main">
        <div class="footer__wrapper-title">
          <p class="footer__wrapper-title-text">Our firm</p>
        </div>

        <p class="footer__wrapper-main-top">Lorem ipsum dolor sit amet,
          consectetur adipiscing elit. Suspendisse varius enim in eros elementum
          tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla,
          ut commodo diam libero vitae erat. Aenean faucibus nibh et justo cursus id
          rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.</p>
        <p class="footer__wrapper-main-middle">Lorem ipsum dolor sit amet,
          consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.
          Duis cursus, mi quis viverra ornare, eros dolor interdum nulla,
          ut commodo diam libero vitae erat. Aenean faucibus nibh et justo cursus id
          rutrum lorem imperdiet.
          Nunc ut sem vitae risus tristique posuere.</p>
        <p class="footer__wrapper-main-bottom">Lorem ipsum dolor sit amet,
          consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique.
          Duis cursus, mi quis viverra ornare, eros dolor interdum nulla,
          ut commodo diam libero vitae erat. Aenean faucibus nibh et justo cursus id
          rutrum lorem imperdiet.
          Nunc ut sem vitae risus tristique posuere.</p>
        <div class="footer__wrapper-footer">
          <p class="footer__wrapper-footer-upper">Stephen Collier</p>
          <p class="footer__wrapper-footer-bottom">Senior Partner</p>
        </div>
      </div>

    </div>
  </div>
</template>

<script>

import "@fontsource/poppins";

export default {
  name: 'mainTheme',
  props: {

  }
}
</script>

<style scoped>
.main__wrapper {
  width: 100%;
}

p {
  margin: 0;
  padding: 0;
}

.header__wrapper {
  height: 566px;
  background-color: #ECE7E4;
  padding: 77px 780px 77px 60px;
  display: flex;
  justify-content: center;
  flex-direction: column-reverse;
}

.header__title {
  margin: 20px 0 18px 0;
}

.header__title-upper-text {
  color: #645C55;
  font-family: 'Poppins';
  font-size: 14px;
}

.header__title-text {
  font-family: 'Poppins';
  font-size: 64px;
  line-height: 70.4px;
}

.header__footer {
  width: 509px;
  font-family: 'Poppins';
  font-size: 16px;
}

.header__footer-text {
  margin-bottom: 41px;
}

.header__right {
  margin-left: 58px;
}

.header__photo {
  width: 720px;
  height: 720px;
}

.footer__wrapper {
  display: flex;
  justify-content: center;
}

.footer__wrapper-title {
  font-family: 'Poppins';
  font-size: 32px;
  display: flex;
  justify-content: center;
  margin-top: 61px;
}


.footer__wrapper-main {
  font-family: 'Poppins';
  font-size: 16px;
}

.footer__wrapper-main>*:not(:first-child) {
  margin: 34px 0 34px 0;
  width: 526px;
  height: 120px;
}

.footer__wrapper-footer {
  font-family: 'Poppins';
}

.footer__wrapper-footer-upper {
  font-size: 17px;
  color: #1B1A1A;
}

.footer__wrapper-footer-bottom {
  color: #645C55;
  font-size: 14px;
}

@media screen and (max-width: 376px) {
  .header__wrapper {
    height: auto;
    padding: 0;
    flex-direction: row;
    justify-content: start;
    flex-wrap: wrap;
  }

  .header__left {
    padding: 10px;
  }

  .header__title-upper-text {
    margin-top: 10px;
    line-height: 20px;
    font-size: 12px;
    letter-spacing: 2px;
  }

  .header__title-text {
    font-size: 28px;
    line-height: 140%;
  }

  .header__footer {
    width: auto;
  }

  .header__right {
    margin-left: 0;
  }

  .header__photo {
    width: 375px;
    height: 375px;
  }

  .footer__wrapper-title {
    margin: 61px 0 -90px 0;
  }

  .footer__wrapper-title-text {
    font-size: 24px;
    line-height: 140%;
  }

  .footer__wrapper-main>*:not(:first-child) {
    margin: 111px 0 -25px 0;
    width: 326px;
  }

}
</style>
