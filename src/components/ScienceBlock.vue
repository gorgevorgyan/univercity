<template>
  <div class="science-block" id="science_click" v-on:click="sc_click">
    <svg class="science-block__bg" width="21.510vw" height="19.375vw">
      <use href="@/assets/img/sprite.svg#science-container"></use>
    </svg>

    <div class="science-block__top">
      <div class="science-block__cols">
        <div class="science-block__col">
          <p class="science-block__title">Научная деятельность</p>
          <p class="science-block__subtitle">Выполнение плана</p>
          <p class="science-block__percent">24,5%</p>

          <svg
            class="science-block__bar"
            width="163"
            height="23"
            viewBox="0 0 163 23"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M6.69088 0.0908813H-2.86102e-05L18.4 23H25.0909L6.69088 0.0908813Z"
              fill="#A7EB17"
            />
            <path
              d="M65.6 0.0908813H58.9091L77.3091 23H84L65.6 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M36.1455 0.0908813H29.4546L47.8546 23H54.5455L36.1455 0.0908813Z"
              fill="#A7EB17"
            />
            <path
              d="M95.0545 0.0908813H88.3636L106.764 23H113.455L95.0545 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M144.145 0.0908813H137.455L155.855 23H162.545L144.145 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M16.5091 0.0908813H9.81821L28.2182 23H34.9091L16.5091 0.0908813Z"
              fill="#A7EB17"
            />
            <path
              d="M75.4182 0.0908813H68.7273L87.1273 23H93.8182L75.4182 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M124.509 0.0908813H117.818L136.218 23H142.909L124.509 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M45.9636 0.0908813H39.2727L57.6727 23H64.3636L45.9636 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M104.873 0.0908813H98.1818L116.582 23H123.273L104.873 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M26.3273 0.0908813H19.6364L38.0364 23H44.7273L26.3273 0.0908813Z"
              fill="#A7EB17"
            />
            <path
              d="M85.2364 0.0908813H78.5454L96.9454 23H103.636L85.2364 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M134.327 0.0908813H127.636L146.036 23H152.727L134.327 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M55.7818 0.0908813H49.0909L67.4909 23H74.1818L55.7818 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
            <path
              d="M114.691 0.0908813H108L126.4 23H133.091L114.691 0.0908813Z"
              fill="#A7EB17"
              fill-opacity="0.2"
            />
          </svg>
        </div>

        <div class="science-block__col">
          <div class="science-block__list">
            <div class="science-block__item">
              <div class="science-block__inf">
                <svg
                  width="0.833vw"
                  height="0.833vw"
                  class="science-block__icon"
                >
                  <use href="@/assets//img/sprite.svg#block-graph-icon4"></use>
                </svg>

                <p class="science-block__text">
                  Поступления от НИР <br />
                  за текущий год <br />
                  <span>123 396,38 тыс.</span>
                </p>
              </div>
            </div>

            <div class="science-block__item">
              <div class="science-block__inf">
                <svg
                  width="0.833vw"
                  height="0.833vw"
                  class="science-block__icon"
                >
                  <use href="@/assets//img/sprite.svg#block-graph-icon5"></use>
                </svg>

                <p class="science-block__text">
                  Ожидаемые поступления <br />
                  от НИР в текущем году <br />
                  <span>74 353,93 тыс.</span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="science-block__bottom">
      <div class="science-block__rows">
        <div class="science-block__btns">
          <button class="science-btn is--active">
            <svg class="science-btn__active">
              <use href="@/assets/img/sprite.svg#science-btn-icon"></use>
            </svg>

            <svg class="science-btn__icon" width="0.521vw" height="0.521vw">
              <use href="@/assets/img/sprite.svg#triangle-icon"></use>
            </svg>
            <span class="science-btn__text">Публикации WoS</span>
          </button>

          <button class="science-btn">
            <svg class="science-btn__icon" width="0.521vw" height="0.521vw">
              <use href="@/assets/img/sprite.svg#triangle-icon"></use>
            </svg>
            <span class="science-btn__text">Публикации Scopus</span>
          </button>

          <button class="science-btn">
            <svg class="science-btn__icon" width="0.521vw" height="0.521vw">
              <use href="@/assets/img/sprite.svg#triangle-icon"></use>
            </svg>
            <span class="science-btn__text">Публикации Q1</span>
          </button>

          <button class="science-btn">
            <svg class="science-btn__icon" width="0.521vw" height="0.521vw">
              <use href="@/assets/img/sprite.svg#triangle-icon"></use>
            </svg>
            <span class="science-btn__text">Публикации Q2</span>
          </button>
        </div>

        <div class="science-block__graph">
          <svg
            width="12.083vw"
            height="6.250vw"
            viewBox="0 0 242 122"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect y="117" width="204" height="1" fill="#B2CEF6" />
            <rect x="14" y="40" width="22" height="77" fill="#217AFF" />
            <rect x="46" y="67" width="22" height="50" fill="#217AFF" />
            <rect x="76" y="47" width="22" height="70" fill="#217AFF" />
            <rect x="108" y="91" width="22" height="26" fill="#217AFF" />
            <rect x="140" y="75" width="22" height="42" fill="#217AFF" />
            <rect x="172" y="26" width="22" height="91" fill="#217AFF" />
            <rect
              x="21.7071"
              y="117.536"
              width="4"
              height="4"
              transform="rotate(-45 21.7071 117.536)"
              fill="white"
              stroke="#B2CEF6"
            />
            <rect
              x="53.7071"
              y="117.536"
              width="4"
              height="4"
              transform="rotate(-45 53.7071 117.536)"
              fill="white"
              stroke="#B2CEF6"
            />
            <rect
              x="83.7071"
              y="117.536"
              width="4"
              height="4"
              transform="rotate(-45 83.7071 117.536)"
              fill="white"
              stroke="#B2CEF6"
            />
            <rect
              x="116.707"
              y="117.536"
              width="4"
              height="4"
              transform="rotate(-45 116.707 117.536)"
              fill="white"
              stroke="#B2CEF6"
            />
            <rect
              x="148.707"
              y="117.536"
              width="4"
              height="4"
              transform="rotate(-45 148.707 117.536)"
              fill="white"
              stroke="#B2CEF6"
            />
            <rect
              x="180.707"
              y="117.536"
              width="4"
              height="4"
              transform="rotate(-45 180.707 117.536)"
              fill="white"
              stroke="#B2CEF6"
            />
            <g filter="url(#filter0_d)">
              <path
                d="M232 22.64V1H191.111L184 8.2V32H222.756L232 22.64Z"
                fill="#112054"
              />
              <path
                d="M232.5 22.64V22.8453L232.356 22.9914L223.111 32.3514L222.964 32.5H222.756H184H183.5V32V8.2V7.99471L183.644 7.84865L190.755 0.648649L190.902 0.5H191.111H232H232.5V1V22.64Z"
                stroke="#217AFF"
              />
            </g>
            <path
              d="M202.86 19V26H201.56V20.09H200.08V19H202.86ZM206.609 18.9C207.569 18.9 208.312 19.2 208.839 19.8C209.372 20.4 209.639 21.26 209.639 22.38C209.639 23.1667 209.495 23.84 209.209 24.4C208.922 24.9533 208.519 25.3767 207.999 25.67C207.485 25.9567 206.889 26.1 206.209 26.1C205.849 26.1 205.509 26.0633 205.189 25.99C204.875 25.91 204.602 25.7967 204.369 25.65L204.849 24.67C205.195 24.8967 205.639 25.01 206.179 25.01C206.852 25.01 207.379 24.8033 207.759 24.39C208.139 23.9767 208.329 23.38 208.329 22.6V22.59C208.122 22.83 207.859 23.0133 207.539 23.14C207.219 23.26 206.859 23.32 206.459 23.32C205.999 23.32 205.585 23.2333 205.219 23.06C204.852 22.88 204.565 22.6267 204.359 22.3C204.152 21.9733 204.049 21.5967 204.049 21.17C204.049 20.7167 204.162 20.32 204.389 19.98C204.615 19.6333 204.922 19.3667 205.309 19.18C205.695 18.9933 206.129 18.9 206.609 18.9ZM206.709 22.3C207.129 22.3 207.469 22.1867 207.729 21.96C207.995 21.7333 208.129 21.4467 208.129 21.1C208.129 20.76 207.999 20.48 207.739 20.26C207.485 20.0333 207.132 19.92 206.679 19.92C206.272 19.92 205.942 20.03 205.689 20.25C205.435 20.4633 205.309 20.75 205.309 21.11C205.309 21.4767 205.435 21.7667 205.689 21.98C205.942 22.1933 206.282 22.3 206.709 22.3ZM212.889 19V26H211.589V20.09H210.109V19H212.889Z"
              fill="white"
            />
            <path
              d="M195.01 8.74H195.72V12.92L199.23 8.74H199.86V14H199.15V9.82L195.65 14H195.01V8.74ZM206.415 8.7C206.908 8.7 207.351 8.81333 207.745 9.04C208.145 9.26667 208.458 9.58333 208.685 9.99C208.911 10.3967 209.025 10.8567 209.025 11.37C209.025 11.8833 208.911 12.3433 208.685 12.75C208.458 13.1567 208.145 13.4767 207.745 13.71C207.351 13.9367 206.908 14.05 206.415 14.05C205.948 14.05 205.525 13.95 205.145 13.75C204.765 13.5433 204.455 13.26 204.215 12.9C203.981 12.54 203.845 12.1267 203.805 11.66H202.605V14H201.895V8.74H202.605V11.01H203.815C203.868 10.5567 204.011 10.1567 204.245 9.81C204.485 9.45667 204.791 9.18333 205.165 8.99C205.538 8.79667 205.955 8.7 206.415 8.7ZM206.415 13.43C206.775 13.43 207.098 13.3433 207.385 13.17C207.678 12.9967 207.908 12.7533 208.075 12.44C208.241 12.1267 208.325 11.77 208.325 11.37C208.325 10.97 208.241 10.6133 208.075 10.3C207.908 9.98667 207.678 9.74667 207.385 9.58C207.098 9.40667 206.775 9.32 206.415 9.32C206.055 9.32 205.728 9.40667 205.435 9.58C205.148 9.74667 204.921 9.98667 204.755 10.3C204.588 10.6133 204.505 10.97 204.505 11.37C204.505 11.77 204.588 12.1267 204.755 12.44C204.921 12.7533 205.148 12.9967 205.435 13.17C205.728 13.3433 206.055 13.43 206.415 13.43ZM210.547 8.74H211.257V11.07H214.567V8.74H215.277V14H214.567V11.68H211.257V14H210.547V8.74ZM219.555 10.6C220.215 10.6067 220.715 10.7533 221.055 11.04C221.402 11.3267 221.575 11.74 221.575 12.28C221.575 12.84 221.388 13.27 221.015 13.57C220.648 13.87 220.115 14.0167 219.415 14.01L217.295 14V8.74H218.005V10.58L219.555 10.6ZM219.375 13.47C219.862 13.4767 220.228 13.38 220.475 13.18C220.728 12.9733 220.855 12.6733 220.855 12.28C220.855 11.8933 220.732 11.6067 220.485 11.42C220.238 11.2333 219.868 11.1367 219.375 11.13L218.005 11.11V13.45L219.375 13.47Z"
              fill="white"
            />
            <defs>
              <filter
                id="filter0_d"
                x="183"
                y="0"
                width="59"
                height="43"
                filterUnits="userSpaceOnUse"
                color-interpolation-filters="sRGB"
              >
                <feFlood flood-opacity="0" result="BackgroundImageFix" />
                <feColorMatrix
                  in="SourceAlpha"
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                />
                <feOffset dx="5" dy="6" />
                <feGaussianBlur stdDeviation="2" />
                <feColorMatrix
                  type="matrix"
                  values="0 0 0 0 0.0897222 0 0 0 0 0.241933 0 0 0 0 0.633333 0 0 0 0.12 0"
                />
                <feBlend
                  mode="normal"
                  in2="BackgroundImageFix"
                  result="effect1_dropShadow"
                />
                <feBlend
                  mode="normal"
                  in="SourceGraphic"
                  in2="effect1_dropShadow"
                  result="shape"
                />
              </filter>
            </defs>
          </svg>
        </div>
      </div>
    </div>

    <div class="progress progress--left1">
      <p class="progress__text">05.07.2021</p>

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
        <path
          d="M22.5 0H18.5L29.5 12H33.5L22.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
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
        <path
          d="M28.5 0H24.5L35.5 12H39.5L28.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
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

    <!-- <Progress class="progress--left1" v-bind:progress="progress.text1" /> -->

    <!-- <Progress class="progress--right1" v-bind:progress="progress.text2" /> -->
    <div class="progress progress--right1">
      <p class="progress__text">55% год</p>
      <svg
        width="100"
        height="12"
        viewBox="0 0 100 12"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path d="M95.5 0H99.5L88.5 12H84.5L95.5 0Z" fill="#F79A2D" />
        <path d="M59.5 0H63.5L52.5 12H48.5L59.5 0Z" fill="#F79A2D" />
        <path d="M77.5 0H81.5L70.5 12H66.5L77.5 0Z" fill="#F79A2D" />
        <path
          d="M41.5 0H45.5L34.5 12H30.5L41.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M11.5 0H15.5L4.5 12H0.5L11.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M89.5 0H93.5L82.5 12H78.5L89.5 0Z" fill="#F79A2D" />
        <path d="M53.5 0H57.5L46.5 12H42.5L53.5 0Z" fill="#F79A2D" />
        <path
          d="M23.5 0H27.5L16.5 12H12.5L23.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M71.5 0H75.5L64.5 12H60.5L71.5 0Z" fill="#F79A2D" />
        <path
          d="M35.5 0H39.5L28.5 12H24.5L35.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M83.5 0H87.5L76.5 12H72.5L83.5 0Z" fill="#F79A2D" />
        <path
          d="M47.5 0H51.5L40.5 12H36.5L47.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path
          d="M17.5 0H21.5L10.5 12H6.5L17.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
        <path d="M65.5 0H69.5L58.5 12H54.5L65.5 0Z" fill="#F79A2D" />
        <path
          d="M29.5 0H33.5L22.5 12H18.5L29.5 0Z"
          fill="#F79A2D"
          fill-opacity="0.2"
        />
      </svg>
    </div>
  </div>
</template>

<script>
import Progress from "./Progress.vue";
export default {
  data() {
    return {
      progress: {
        text1: "05.07.2021",
        text2: "55% год",
      },
    };
  },

  methods: {
    sc_click: function () {
      this.connection.send("sc_click");
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
.science-block {
  position: relative;
  width: 21.51vw;
  height: 19.375vw;
  z-index: 0;
  margin-left: auto;
  margin-right: auto;
  cursor: pointer;
}

.progress--right .progress__icon {
  transform: scaleX(-1);
}

.science-btn__active {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  left: 0;
  width: 8.292vw;
  height: 2.615vw;
}

.science-btn__icon {
  stroke: #d2daef;
  margin-right: 0.313vw;
  flex: 0 0 auto;
}

.science-btn__text {
  font-size: 0.66vw;
  letter-spacing: 0.03em;
  color: #fff;
}

.science-btn {
  display: flex;
  align-items: center;
  width: 7.8vw;
  height: 1.615vw;
  position: relative;
  padding-left: 0.5vw;
  margin-bottom: 0.2vw;

  &.is--active {
    .science-btn__icon {
      stroke: #217aff;
    }
  }
}

.science-block__percent {
  font-weight: 700;
  font-size: 0.781vw;
  line-height: 1.042vw;
  color: #f79a2d;
  margin-bottom: 0.208vw;
}

.science-block__rows {
  display: flex;
}

.science-block__btns {
  width: 9.292vw;
  margin-right: 0.521vw;
  flex: 0 0 auto;
  padding-left: 1.563vw;
}

.science-block__title {
  font-size: 0.938vw;
  line-height: 1.042vw;
  letter-spacing: 0.05em;
  margin-bottom: 1.7vw;
}

.science-block__cols {
  display: flex;
}

.science-block__col {
  padding-top: 1.354vw;
  padding-left: 1.302vw;
  padding-right: 1.302vw;

  &:first-of-type {
    width: 11.771vw;
  }

  &:last-of-type {
    width: 10.417vw;
    padding-left: 0;
  }
}

.science-block__inf {
  display: flex;
  align-items: flex-start;
}

.science-block__icon {
  position: relative;
  top: 0.2vw;
  margin-right: 0.104vw;
}

.science-block__text {
  font-size: 0.677vw;
  letter-spacing: 0.03em;
  color: #cdd6ee;

  span {
    display: block;
    margin-top: 0.313vw;
    color: #ffffff;
  }
}

.science-block__bg {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
}

.science-block__list {
  padding-top: 0.5vw;
}

.science-block__item {
  margin-bottom: 0.625vw;
}

.science-block__bar {
  width: 8vw;
  height: 1.146vw;
}

.science-block__top {
  position: relative;
  &:after {
    content: "";
    position: absolute;
    left: 1.563vw;
    right: 1.563vw;
    bottom: 0;
    border: 1px dashed rgba(33, 122, 255, 0.2);
  }
}

.science-block__bottom {
  padding-top: 0.625vw;
}
</style>
