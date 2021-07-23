<template>
  <div class="rating" v-on:click="memb_click">
    <svg class="rating__box" width="21.719vw" height="16.927vw">
      <use href="@/assets/img/sprite.svg#rating-box-icon"></use>
    </svg>
    <p class="rating__title">Кадры</p>
    <div class="progress progress--left">
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

    <!-- <Progress class="progress--left" v-bind:progress="progress.text1" /> -->

    <!-- <Progress class="progress--right" v-bind:progress="progress.text2" /> -->
	<div class="progress progress--right">
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

    <div class="rating__wrapper">
      <div class="rating__list">
        <div class="rating__item">
          <p class="rating__name">Севастопольский</p>
          <div class="rating__wrap">
            <ProgressSecond line_42/>
            <span class="rating__value">42</span>
          </div>

          <div class="rating__wrap">
            <ProgressSecond progress_red />
            <span class="rating__value rating__value--red">X</span>
          </div>
        </div>

        <div class="rating__item">
          <p class="rating__name">Тульский</p>
          <div class="rating__wrap">
            <ProgressSecond line_37 />
            <span class="rating__value">37</span>
          </div>

          <div class="rating__wrap">
            <ProgressSecond progress_red />
            <span class="rating__value rating__value--red">X</span>
          </div>
        </div>

        <div class="rating__item">
          <p class="rating__name">Волгоградский</p>
          <div class="rating__wrap">
            <ProgressSecond line_78/>
            <span class="rating__value">78</span>
          </div>

          <div class="rating__wrap">
            <ProgressSecond progress_red />
            <span class="rating__value rating__value--red">X</span>
          </div>
        </div>
      </div>
      <img src="@/assets/img/graph.svg" alt="" />
    </div>

    <div class="rating__rows">
      <div class="rating__row">
        <div class="rating__info">
          <svg class="rating__info-icon" width="0.833vw" height="0.833vw">
            <use href="@/assets/img/sprite.svg#info-icon1"></use>
          </svg>
          <span class="rating__info-text">Кол-во сотрудников</span>
        </div>
      </div>

      <div class="rating__row">
        <div class="rating__info">
          <svg class="rating__info-icon" width="0.833vw" height="0.833vw">
            <use href="@/assets/img/sprite.svg#info-icon2"></use>
          </svg>
          <span class="rating__info-text">Преподавателей</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Progress from "./Progress.vue";
import ProgressSecond from "./ProgressSecond.vue";
export default {
  name: "Rating",
  data() {
    return {
      progress: {
        text1: "85% месяц",
        text2: "55% год",
      },
    };
  },
  methods: {
    memb_click: function () {
      this.connection.send("memb_click");
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
    ProgressSecond,
  },
};
</script>

<style lang="scss">
.rating__list {
  position: absolute;
  top: 4.1vw;
  left: 2.2vw;
  right: 2.2vw;
}

.rating__name {
  font-size: 0.469vw;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  font-weight: 700;
  line-height: 0.573vw;
  margin-bottom: 0.417vw;
}

.rating__item:not(:last-of-type) {
  margin-bottom: 0.6vw;
}

.rating__wrap {
  display: flex;
  align-items: center;
}

.rating__value {
  font-weight: bold;
  font-size: 0.521vw;
  color: #fb9b2b;
  margin-left: 0.156vw;

  &--red {
    color: #ff5a5a;
  }
}

.rating__rows {
  position: absolute;
  z-index: 1;
  left: 50%;
  transform: translateX(-50%);
  bottom: 2.4vw;
}

.rating__row {
  &:not(:last-of-type) {
    margin-bottom: 0.156vw;
  }
}

.rating__info {
  display: flex;
  align-items: center;
}

.rating__info-icon {
  flex: 0 0 auto;
  margin-right: 0.521vw;
}
.rating__info-text {
  font-size: 0.677vw;
  line-height: 0.833vw;
  letter-spacing: 0.03em;
}
.rating__wrapper {
  width: 18.698vw;
  height: 10.417vw;
  margin: -0.9vw auto 0;

  img {
    position: relative;
    z-index: 1;
    width: 18.698vw;
    height: 10.417vw;
  }
}
.rating {
  margin-top: 5.99vw;
  width: 21.51vw;
  height: 18.021vw;
  position: relative;
  z-index: 0;
  cursor: pointer;
}

.rating__box {
  position: absolute;
  z-index: -1;
}

.rating__title {
  font-size: 0.938vw;
  line-height: 1.042vw;
  letter-spacing: 0.05em;
  padding: 1.563vw;
}

.progress--left {
  bottom: 1.6vw;
  left: 0.5vw;
}

.progress--right {
  bottom: 1.6vw;
  right: 0.8vw;
  text-align: right;
}

.progress--right .progress__icon {
  transform: scaleX(-1);
}
</style>
