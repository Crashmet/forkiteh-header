<template>
  <div id="app">
    <header class="header">
      <section class="header__top">
        <div class="container-fluid header__line header__line_top">
          <a class="header__left header-logo__container" href="#"
            ><svg
              viewBox="0 0 90 34"
              width="90"
              height="34"
              class="header__logo"
            >
              <use
                xlink:href="#darkLogoFill"
                transform="translate(.6 .42)"
                fill="#fff"
              ></use>
              <defs>
                <path
                  id="darkLogoFill"
                  fill-rule="evenodd"
                  d="M77.447.143c3.36-.495 6.436.308 8.508 2.256 1.915 1.762 2.888 4.265 2.637 6.923-.44 4.915-2.857 8.872-9.638 15.394l-11.082.371s7.692-6.924 10.611-10.293c1.884-2.194 2.7-4.544 1.915-6.12-.502-.99-1.6-1.484-2.95-1.422V.142zM54.75 4.037v6.399l9.606-1.02V2.708l-9.606 1.33zM46.902 33V5.12l6.592-.929v28.81h-6.592zM20.814 8.735v5.41l7.283-.804V7.746l-7.283.99zM14.818 33V9.57l5.054-.71V33h-5.054zM0 11.61v4.791l13.06-1.421V9.817L0 11.61zm4.175 5.069V33h4.772V16.185l-4.772.494zm16.639 6.956v-5.503l4.771-.402v5.657l-4.771.248zm0 3.956V33h7.283v-5.627l-7.283.217zm33.936-5.78v-6.522l6.31-.556v6.738l-6.31.34zm0 4.792V33h9.606v-6.708l-9.606.31zM30.012 33V7.468l5.745-.804V33h-5.745zm6.812-5.873V33h8.32v-6.12l-8.32.247zm29.667-.896l.031 6.77H89v-7.42l-22.509.65zm.314-12.149C66.428 6.355 69.63 1.626 76.16.266l.031 7.233c-1.38.556-2.73 1.608-2.417 5.965l-6.97.618z"
                ></path>
              </defs>
            </svg>
          </a>
          <div class="header__right">
            <button class="header-region__button" id="region-search-opener">
              <span class="header-region-button__icon icon-location">
                <svg
                  width="14"
                  height="18"
                  viewBox="0 0 14 18"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    clip-rule="evenodd"
                    d="M7 0.0625C3.57444 0.100105 0.8125 2.885 0.8125 6.31455C0.8125 6.33228 0.8125 6.35054 0.8125 6.36827C0.8125 9.70059 6.35196 16.7504 6.58786 17.0485C6.68458 17.1716 6.83289 17.25 7 17.25C7.16711 17.25 7.31542 17.1716 7.41107 17.0496C7.64804 16.7504 13.1875 9.70059 13.1875 6.36559C13.1875 6.35054 13.1875 6.33282 13.1875 6.31455C13.1875 2.88446 10.425 0.100105 7.00322 0.0625H7ZM7 15.8398C5.25847 13.5486 1.87107 8.62402 1.87107 6.36559C1.87053 6.33873 1.86999 6.30649 1.86999 6.2748C1.86999 3.44209 4.16659 1.14605 7 1.14605C9.83341 1.14605 12.13 3.44209 12.13 6.2748C12.13 6.30649 12.1295 6.33873 12.1289 6.37042C12.1289 8.62294 8.74099 13.5465 6.99946 15.8387L7 15.8398ZM7 3.64515C6.98388 3.64462 6.96507 3.64462 6.94627 3.64462C5.37346 3.64462 4.09835 4.91942 4.09835 6.49183C4.09835 8.06424 5.37346 9.33904 6.94627 9.33904C8.51907 9.33904 9.79364 8.06478 9.79418 6.49237C9.79418 6.48485 9.79418 6.47571 9.79418 6.46658C9.79418 4.9178 8.54701 3.65966 7.00161 3.64247L7 3.64515ZM7 8.26033C6.99033 8.26033 6.97851 8.26086 6.96668 8.26086C5.98926 8.26086 5.19722 7.46902 5.19722 6.49183C5.19722 5.51465 5.98926 4.7228 6.96668 4.7228C7.94411 4.7228 8.73615 5.51465 8.73615 6.49183C8.73615 6.49237 8.73615 6.49237 8.73615 6.4929C8.73615 6.49613 8.73615 6.50043 8.73615 6.50419C8.73615 7.46633 7.96077 8.24797 7.00107 8.25818L7 8.26033Z"
                    fill="#7C8792"
                  /></svg></span
              >Москва и область
            </button>
            <button
              class="header-notifications__button"
              id="notifications-search-opener"
            >
              <div class="header-notifications-button__icon notification-box">
                <div class="notification-bell">
                  <span class="bell-top"></span>
                  <span class="notification-count"></span>
                  <span class="bell-middle"></span>
                  <span class="bell-bottom"></span>
                  <span class="bell-rad"></span>
                </div>
              </div>
            </button>
          </div>
        </div>
      </section>
      <section class="header_white">
        <div class="container-fluid header__line header__line_bottom">
          <nav class="header__nav">
            <ul class="header-nav__list">
              <li class="header__nav-item">Преимущества Tele2</li>
              <li class="header__nav-item">Тарифы</li>
              <li class="header__nav-item">Акции и спецпредложения</li>
              <li class="header__nav-item">Промотариф Tele2</li>
              <li class="header__nav-item">Технология eSIM</li>
              <li class="header__nav-item">Подключение нового абонента</li>
            </ul>
          </nav>
        </div>
      </section>
    </header>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {},
};
</script>

<style src="@/styles/fonts/fonts.css"></style>
<style src="@/styles/normalize.css"></style>
<style src="@/styles/allBaseStyle.css"></style>
<style>
:root {
  --base-font-family: 'tele2_textsans_regular', sans-serif;
  --bold-font-family: 'tele2_displayserif-bold', serif;
  --regular-title-font-family: 'tele2_displayserif-regular', serif;
  --banner-font-family: 'Standart CT Stencil';
}

.header__top {
  background-color: #1f2229;
}

.header__line {
  height: 2.5rem;
  display: flex;
  align-items: center;
}

.header__line_top {
  justify-content: space-between;
}

.header-logo__container {
  display: flex;
  align-items: center;
}

.header__logo {
  min-width: 3.6875rem;
  max-width: 1.375rem;
}

.header__right {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.header-region__button {
  display: flex;
  align-items: center;
  margin-right: 2.3125rem;
  font-family: var(--base-font-family);
  font-style: normal;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.125rem;
  color: #7c8792;
  background-color: #1f2229;
  opacity: 0.9;
}

.header-region__button:hover,
.header-region__button:active {
  color: #d2dae2;
  transition: color 0.3s ease-in;
}

.header-region-button__icon {
  margin-right: 0.75rem;
  width: 0.875rem;
  height: 1.25rem;
}

.notification-box {
  text-align: center;
  background-color: #1f2229;
}

.notification-bell {
  animation: bell 1s 1s both infinite;
}

.notification-bell * {
  display: block;
  margin: 0 auto;
  background-color: transparent;
  border: 0.125rem solid #fff;
  border-bottom: 0;
  /* box-shadow: 0rem 0rem 0.9375rem #fff; */
}

.bell-top {
  width: 0.375rem;
  height: 0.25rem;
  border-radius: 0.1875rem 0.1875rem 0 0;
}

.bell-middle {
  position: relative;
  width: 0.9375rem;
  height: 0.875rem;
  margin-top: -0.0625rem;
  border-radius: 0.7813rem 0.7813rem 0 0;
}
.bell-bottom {
  position: relative;
  z-index: 0;
  width: 1.125rem;
  height: 0.0625rem;
  background-color: #fff;
}
.bell-bottom::before,
.bell-bottom::after {
  content: '';
  position: absolute;
  top: -0.25rem;
}

.bell-rad {
  width: 0.3625rem;
  height: 0.1875rem;
  margin-top: 0.0625rem;
  background-color: transparent;
  border-bottom: 0.1062rem solid #fff;
  border-top: 0;
  border-radius: 0 0 3.125rem 3.125rem;
  animation: rad 1s 3s both infinite;
}

.notification-count {
  position: absolute;
  z-index: 1;
  right: -0.1938rem;
  top: 0.1062rem;
  width: 0.6875rem;
  height: 0.6875rem;
  border-radius: 50%;
  background: #3fcbff;
  border: 0.1563rem solid #1f2229;
  /* animation: zoom 3s 3s both infinite; */
}
@keyframes bell {
  0% {
    transform: rotate(0);
  }
  10% {
    transform: rotate(30deg);
  }
  20% {
    transform: rotate(0);
  }
  80% {
    transform: rotate(0);
  }
  90% {
    transform: rotate(-30deg);
  }
  100% {
    transform: rotate(0);
  }
}
@keyframes rad {
  0% {
    transform: translateX(0);
  }
  10% {
    transform: translateX(0.375rem);
  }
  20% {
    transform: translateX(0);
  }
  80% {
    transform: translateX(0);
  }
  90% {
    transform: translateX(-0.375rem);
  }
  100% {
    transform: translateX(0);
  }
}
@keyframes zoom {
  0% {
    opacity: 0;
    transform: scale(0);
  }
  10% {
    opacity: 1;
    transform: scale(1);
  }
  50% {
    opacity: 1;
  }
  51% {
    opacity: 0;
  }
  100% {
    opacity: 0;
  }
}

.header__line_bottom {
  position: relative;
  height: 2.9375rem;
}

.header__line_bottom::after {
  content: '';
  position: absolute;
  bottom: 0;
  z-index: -1;
  width: 97%;
  height: 0.0625rem;
  background: #d3d9df;
}

.header-nav__list {
  display: flex;
  align-items: center;
}

.header__nav-item {
  position: relative;
  font-family: var(--base-font-family);
  font-style: normal;
  font-weight: 400;
  font-size: 0.875rem;
  line-height: 1.125rem;
  color: #7c8792;
}

.header__nav-item:not(:last-child) {
  margin-right: 1.125rem;
}

.header__nav-item:hover,
.header__nav-item:active {
  color: #1f2229;
  transition: color 0.3s ease-in;
}

.header__nav-item:hover::after,
.header__nav-item:active::after {
  content: '';
  position: absolute;
  z-index: 10;
  bottom: -0.875rem;
  right: 0;
  width: 100%;
  height: 0.125rem;
  background-color: #1f2229;
  transition: height 0.3s ease-in;
}

@media (max-width: 900px) {
  .header__line_top {
    height: 45px;
    margin-bottom: 16px;
  }

  .header-region__button {
    display: none;
  }

  .header__line_bottom {
    padding: 0px 15px;
    gap: 16px;
    height: 260px;
  }

  .header__line_bottom::after {
    display: none;
  }

  .header-nav__list {
    position: relative;
    flex-direction: column;
    align-items: start;
    flex-grow: 1;
    min-width: 350px;
  }

  .header__nav-item {
    padding: 8px 0 10px;
    width: 100%;
    font-family: var(--base-font-family);
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 22px;
    border-bottom: 1px solid #ededed;
    color: #959597;
  }

  .header__nav-item:not(:last-child) {
    margin-right: 0;
    margin-bottom: 8px;
  }

  .header__nav-item:hover,
  .header__nav-item:active {
    color: #1f2229;
    transition: color 0.3s ease-in;
  }

  .header__nav-item:hover::after,
  .header__nav-item:active::after {
    content: '';
    position: absolute;
    z-index: 10;
    bottom: 0;
    right: 0;
  }
}
</style>
