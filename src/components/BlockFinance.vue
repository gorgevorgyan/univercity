<template>
  <div class="finance-block" id="fin_click" v-on:click="fin_click">
    <svg class="finance-block__bg" width="22.865vw" height="22.135vw">
      <use href="@/assets/img/sprite.svg#finance-container"></use>
    </svg>

    <div class="finance-block__top">
      <p class="finance-block__title">Финансы</p>

      <div class="finance-block__text">
        <p>7 095 762 667 руб.</p>
        <span>Основные средства на балансе</span>
      </div>
    </div>

    <div class="finance-block__bottom">
      <img
        class="finance-block__graph"
        src="@/assets/img/graph_finance.svg"
        alt=""
      />

      <div class="finance-block__row">
        <div class="finance-block__circle">
          <div class="circle-wrap">
            <svg
              width="6.563vw"
              height="6.510vw"
              viewBox="0 0 126 125"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M62.8976 5C53.4417 5 44.1317 7.33203 35.7923 11.7895C27.4529 16.247 20.3415 22.6924 15.0881 30.5547C9.83465 38.417 6.6013 47.4536 5.67446 56.864C4.74762 66.2744 6.15588 75.7682 9.77451 84.5043C13.3931 93.2404 19.1104 100.949 26.42 106.948C33.7295 112.947 42.4056 117.05 51.6799 118.895C60.9541 120.74 70.5402 120.269 79.5889 117.524C88.6377 114.779 96.8699 109.845 103.556 103.159L91.3348 90.9372C86.6582 95.6137 80.9006 99.0648 74.5717 100.985C68.2429 102.904 61.5383 103.234 55.0518 101.944C48.5652 100.653 42.497 97.7832 37.3846 93.5876C32.2723 89.392 28.2735 84.0003 25.7426 77.8901C23.2117 71.7799 22.2267 65.1399 22.875 58.5581C23.5232 51.9764 25.7847 45.656 29.459 40.157C33.1333 34.658 38.1071 30.15 43.9398 27.0324C49.7724 23.9148 56.284 22.2837 62.8976 22.2837V5Z"
                fill="#217AFF"
              />
              <path
                d="M107.092 106.694C115.833 97.9534 121.785 86.817 124.197 74.6931C126.608 62.5693 125.371 50.0027 120.64 38.5823C115.91 27.1619 107.899 17.4007 97.6207 10.5331C87.3427 3.66556 75.2589 -1.47407e-07 62.8976 0V19.8203C71.3388 19.8203 79.5905 22.3234 86.6091 27.0131C93.6278 31.7028 99.0981 38.3685 102.328 46.1672C105.559 53.9659 106.404 62.5473 104.757 70.8264C103.11 79.1054 99.0455 86.7102 93.0767 92.6791L107.092 106.694Z"
                fill="#2BD6FB"
              />
              <rect
                x="104.571"
                y="23.571"
                width="7"
                height="7"
                transform="rotate(-90 104.571 23.571)"
                fill="white"
                stroke="#2BD6FB"
                stroke-width="3"
              />
              <rect
                x="18.787"
                y="105.785"
                width="7"
                height="7"
                transform="rotate(-88.7585 18.787 105.785)"
                fill="white"
                stroke="#2E81FE"
                stroke-width="3"
              />
            </svg>

            <p class="circle-wrap__val1">863 484 207</p>

            <p class="circle-wrap__val2">1 157 361 264</p>

            <p class="circle-wrap__value">Фонд<br />оплаты<br />труда</p>
          </div>
        </div>

        <div class="finance-block__list">
          <div class="finance-block__item">
            <div class="finance-block__inf">
              <svg width="0.833vw" height="0.833vw" class="finance-block__icon">
                <use href="@/assets/img/sprite.svg#block-graph-icon1"></use>
              </svg>

              <span>Из средств бюджета</span>
            </div>
          </div>

          <div class="finance-block__item">
            <div class="finance-block__inf">
              <svg width="0.833vw" height="0.833vw" class="finance-block__icon">
                <use href="@/assets/img/sprite.svg#block-graph-icon6"></use>
              </svg>

              <span
                >Из средств от иной <br />
                приносящей доход <br />
                деятельности
              </span>
            </div>
          </div>
        </div>
      </div>

      <div class="finance-block__row">
        <div class="finance-block__circle">
          <div class="circle-wrap">
            <svg
              width="6.771vw"
              height="6.771vw"
              viewBox="0 0 130 131"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M112.119 95.9138C119.072 85.118 122.117 72.2656 120.744 59.4979C119.372 46.7303 113.667 34.8182 104.578 25.7464L96.3156 34.0243C103.512 41.207 108.029 50.6386 109.115 60.7477C110.202 70.8568 107.792 81.0329 102.286 89.5807L112.119 95.9138Z"
                fill="#FB9B2B"
              />
              <path
                d="M64.8976 8C54.9251 8 45.1241 10.5936 36.4569 15.5262C27.7897 20.4588 20.5545 27.5607 15.4615 36.1347C10.3685 44.7086 7.59303 54.4597 7.40753 64.4304C7.22203 74.4012 9.6329 84.2487 14.4034 93.0062C19.1739 101.764 26.14 109.13 34.6177 114.381C43.0954 119.633 52.7932 122.589 62.7588 122.96C72.7243 123.331 82.6151 121.104 91.4597 116.497C100.304 111.89 107.799 105.062 113.207 96.6839L98.686 87.3104C94.9033 93.1705 89.6615 97.946 83.4755 101.168C77.2894 104.39 70.3717 105.948 63.4017 105.688C56.4316 105.429 49.6489 103.361 43.7195 99.6882C37.79 96.0152 32.9178 90.8632 29.5813 84.7382C26.2447 78.6131 24.5585 71.7256 24.6883 64.7519C24.818 57.7782 26.7592 50.9582 30.3213 44.9615C33.8834 38.9648 38.9439 33.9976 45.0058 30.5477C51.0677 27.0978 57.9227 25.2837 64.8976 25.2837V8Z"
                fill="#FD6A6A"
              />
              <path
                d="M109.092 21.3058C97.3708 9.58482 81.4737 3.00002 64.8976 3L64.8976 22.8203C76.217 22.8203 87.0727 27.3169 95.0767 35.3209L109.092 21.3058Z"
                fill="#FFC01D"
              />
              <rect
                x="87.3742"
                y="13.6751"
                width="7"
                height="7"
                transform="rotate(-115.824 87.3742 13.6751)"
                fill="white"
                stroke="#FFC01D"
                stroke-width="3"
              />
              <rect
                x="23.4808"
                y="26.4784"
                width="7"
                height="7"
                transform="rotate(-88.5032 23.4808 26.4784)"
                fill="white"
                stroke="#FD6A6A"
                stroke-width="3"
              />
              <rect
                x="114.271"
                y="91.6378"
                width="7"
                height="7"
                transform="rotate(-114.55 114.271 91.6378)"
                fill="white"
                stroke="#FB9B2B"
                stroke-width="3"
              />
            </svg>

            <p class="circle-wrap__val3">2 020 845 472</p>

            <p class="circle-wrap__val4">30 057 927</p>

            <p class="circle-wrap__val5">40 374 475</p>

            <p class="circle-wrap__value is--orange">Затраты</p>
          </div>
        </div>

        <div class="finance-block__list">
          <div class="finance-block__item">
            <div class="finance-block__inf">
              <svg width="0.833vw" height="0.833vw" class="finance-block__icon">
                <use href="@/assets/img/sprite.svg#block-graph-icon7"></use>
              </svg>

              <span>Фонд оплаты труда</span>
            </div>
          </div>

          <div class="finance-block__item">
            <div class="finance-block__inf">
              <svg width="0.833vw" height="0.833vw" class="finance-block__icon">
                <use href="@/assets/img/sprite.svg#block-graph-icon2"></use>
              </svg>

              <span>Земельный налог </span>
            </div>
          </div>

          <div class="finance-block__item">
            <div class="finance-block__inf">
              <svg width="0.833vw" height="0.833vw" class="finance-block__icon">
                <use href="@/assets/img/sprite.svg#block-graph-icon8"></use>
              </svg>

              <span>Имущественный налог</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="progress progress--left1">
      <p class="progress__text">09.07.2021</p>
      <svg
        class="progress__icon"
        width="100"
        height="12"
        viewBox="0 0 100 12"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path d="M4.5 0H0.5L11.5 12H15.5L4.5 0Z" fill="#F79A2D" />
        <path
          d="M40.5 0H36.5L47.5 12H51.5L40.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M22.5 0H18.5L29.5 12H33.5L22.5 0Z" fill="#F79A2D" />
        <path
          d="M58.5 0H54.5L65.5 12H69.5L58.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M88.5 0H84.5L95.5 12H99.5L88.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M10.5 0H6.5L17.5 12H21.5L10.5 0Z" fill="#F79A2D" />
        <path
          d="M46.5 0H42.5L53.5 12H57.5L46.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M76.5 0H72.5L83.5 12H87.5L76.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M28.5 0H24.5L35.5 12H39.5L28.5 0Z" fill="#F79A2D" />
        <path
          d="M64.5 0H60.5L71.5 12H75.5L64.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M16.5 0H12.5L23.5 12H27.5L16.5 0Z" fill="#F79A2D" />
        <path
          d="M52.5 0H48.5L59.5 12H63.5L52.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M82.5 0H78.5L89.5 12H93.5L82.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M34.5 0H30.5L41.5 12H45.5L34.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M70.5 0H66.5L77.5 12H81.5L70.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
      </svg>
    </div>

    <!-- <Progress class="progress--left1" v-bind:progress="progress.text1"/> -->

    <Progress class="progress--right1" v-bind:progress="progress.text2" />
  </div>
</template>

<script>
import Progress from "./Progress.vue";

export default {
  name: "BlockFinance",
  data() {
    return {
      progress: {
        text1: "09.07.2021",
        text2: "65% год",
        scaleLeft: "img/scale-finance-left.svg",
      },
    };
  },
  methods: {
    fin_click: function () {
      this.connection.send("fin_click");
    },
  },
  created() {
    const ws_url = "ws://195.211.102.43:8999";
    this.connection = new WebSocket(ws_url);

    this.connection.onerror = (error) => {
      console.log(error);
    };
  },

  components: {
    Progress,
  },
};
</script>

<style lang="scss" scoped>
.finance-block {
  cursor: pointer;
}

.finance-block__list {
  padding-top: 1vw;
  padding-left: 2vw;
}

.circle-wrap__val1,
.circle-wrap__val2,
.circle-wrap__val3,
.circle-wrap__val4,
.circle-wrap__val5 {
  position: absolute;
  font-size: 0.469vw;
}

.circle-wrap__val1 {
  top: -0.2vw;
  right: -1.5vw;
}

.circle-wrap__val2 {
  bottom: -0.2vw;
  left: -1.5vw;
}

.circle-wrap__val3 {
  top: 0;
  left: -1.2vw;
}

.circle-wrap__val4 {
  top: -0.8vw;
  right: 0;
}

.circle-wrap__val5 {
  bottom: 1.2vw;
  right: -2vw;
}

.finance-block__inf {
  display: flex;
  align-items: flex-start;
  span {
    font-size: 0.677vw;
    letter-spacing: 0.03em;
    color: #fff;
  }
}

.finance-block__item {
  margin-bottom: 1.042vw;
}

.circle-wrap {
  position: relative;

  svg {
    transform: translateX(-0.2vw);
  }
}

.circle-wrap__value {
  font-size: 0.469vw;
  text-transform: uppercase;
  font-weight: 700;
  text-align: center;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  color: #fff;

  &:after {
    content: "";
    border-radius: 50%;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 3.594vw;
    height: 3.594vw;
    border: 1px solid #217aff;
  }

  &.is--orange:after {
    border-color: #fd6a6a;
  }
}

.finance-block__icon {
  flex: 0 0 auto;
  margin-right: 0.26vw;
}

.finance-block__row {
  display: flex;
  padding-top: 1vw;
}

.finance-block__circle {
  width: 10.417vw;
  margin-right: 0.521vw;
  padding-left: 4vw;
}

.finance-block__graph {
  width: 19.688vw;
  height: 15.365vw;
  position: absolute;
  left: 50%;
  top: 0;
  transform: translateX(-50%);
}

.finance-block__bottom {
  margin-top: -1vw;
  position: relative;
}

.finance-block__top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.563vw;
}

.progress--right .progress__icon {
  transform: scaleX(-1);
}

.progress--left1 {
  bottom: 0.4vw;
  left: 0.8vw;
}

.progress--right1 {
  bottom: 0.6vw;
  right: 0.8vw;
}

.finance-block {
  position: relative;
  width: 22.865vw;
  height: 22.135vw;
  margin-bottom: 1.5vw;
  margin-left: auto;
  margin-right: auto;
  z-index: 0;
  display: block;
}

.finance-block__bg {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
}

.finance-block__title {
  font-size: 0.938vw;
  line-height: 1.042vw;
  letter-spacing: 0.05em;
}

.finance-block__text {
  font-size: 0.938vw;
  line-height: 1.042vw;
  letter-spacing: 0.05em;

  span {
    font-size: 0.469vw;
    color: #627dae;
    text-transform: uppercase;
  }
}
</style>
