<template>
  <main class="layout">
    <ul class="layout-link" v-if="showPort == false">
      <li class="layout-link__item">
        <router-link :to="{ name: 'test' }" class="layout-link__router">
          <svg width="2.708vw" height="2.708vw" fill="none">
            <use href="@/assets/img/sprite.svg#nav-link-icon"></use>
          </svg>
        </router-link>
      </li>

      <li class="layout-link__item" v-if="showPort == false">
        <router-link :to="{ name: 'test2' }" class="layout-link__router">
          <svg width="2.708vw" height="2.708vw" fill="none">
            <use href="@/assets/img/sprite.svg#nav-link-icon"></use>
          </svg>
        </router-link>
      </li>

      <!-- <div class="prt-block" id="prt_click" v-on:click="prt_click">
        <li class="layout-link__item">
          <router-link :to="{ name: 'testp' }" class="layout-link__router">
            <svg width="2.708vw" height="2.708vw" fill="none">
              <use href="@/assets/img/sprite.svg#nav-link-icon"></use>
            </svg>
          </router-link>
        </li>
      </div>

      <div class="prt-block" id="prt2_click" v-on:click="prt2_click">
        <li class="layout-link__item">
          <router-link :to="{ name: 'testp2' }" class="layout-link__router">
            <svg width="2.708vw" height="2.708vw" fill="none">
              <use href="@/assets/img/sprite.svg#nav-link-icon"></use>
            </svg>
          </router-link>
        </li>
      </div> -->
    </ul>

    <a class="portrets__btn" v-on:click="prt_click" v-if="showPort == false">
      <svg
        width="92"
        height="52"
        viewBox="0 0 92 52"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M91.5 38V38.2942L91.2428 38.4371L67.8428 51.4371L67.7296 51.5H67.6H1H0.5V51V11V10.7058L0.757179 10.5629L18.7572 0.562921L18.8704 0.5H19H91H91.5V1V38Z"
          stroke="#217AFF"
          stroke-opacity="0.4"
        />
      </svg>

      <!-- <img src="assets/img/portrets-btn.svg" alt="" /> -->
      <p class="portrets__btn-text">Портреты</p>
    </a>

    <div class="cols" v-if="showPort == false">
      <div class="col col--left">
        <BlockFinance />
        <BlockScience />
      </div>

      <div class="col col--middle" v-if="showPort == false">
        <BlockCircle />
        <BlockDown />
      </div>

      <div class="col col--right" v-if="showPort == false">
        <BlockGlobus />
        <BlockRating />
      </div>
    </div>

    <div class="video" v-if="showPort == true">
      <video autoplay="" loop="" muted="" playsinline="">
        <source
          src="../assets/img/video.mp4"
          type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'
        />
        Тег video не поддерживается вашим браузером.
      </video>
    </div>
    <img
      v-if="showPort == true"
      @click="handler"
      :src="urlImg"
      alt=""
      class="test-img portret__foto"
      height="95%"
      width="auto"
    />
    <div class="portret__title" v-if="showPort == true">
      Вишняков Алексей Семенович<br />Предприниматель, Основатель РЭУ<br />
      1859 - 1919 гг.
    </div>

    <div
      class="prt-block"
      id="noprt_click"
      v-on:click="noprt_click"
      v-if="showPort == true"
    >
      <router-link :to="{ name: 'homepage' }">
        <svg
          width="52"
          height="52"
          viewBox="0 0 52 52"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="test"
        >
          <path
            d="M51.5 38V38.2071L51.3536 38.3536L38.3536 51.3536L38.2071 51.5H38H1H0.5V51V11V10.7929L0.646446 10.6464L10.6464 0.646447L10.7929 0.5H11H51H51.5V1V38Z"
            stroke="#217AFF"
            stroke-opacity="0.4"
          />
          <path
            d="M32.6657 17C35.2923 18.9086 37 22.0048 37 25.5C37 31.299 32.299 36 26.5 36C20.701 36 16 31.299 16 25.5C16 22.0048 17.7077 18.9086 20.3343 17"
            stroke="#217AFF"
            stroke-width="2"
          />
          <path d="M26.5 13V27" stroke="#217AFF" stroke-width="2" />
        </svg>
      </router-link>
    </div>
  </main>
</template>

<script>
import BlockCircle from "../components/Circle.vue";
import BlockGlobus from "../components/Globus.vue";
import BlockRating from "../components/Rating.vue";
import BlockDown from "../components/BlockDown.vue";
import BlockScience from "../components/ScienceBlock.vue";
import BlockFinance from "../components/BlockFinance.vue";

export default {
  name: "Homepage",
  data() {
    return {
      activeGif: false,
      urlImg: "/img/gif2.png",
      showPort: false,
    };
  },
  methods: {
    prt_click: function () {
      this.urlImg = "/img/gif1.png";

      this.connection.send("prt2_click");
    },
    noprt_click: function () {
      this.connection.send("noprt_click");
    },

    prt2_click: function () {
      //this.connection.send("prt2_click");
    },
  },
  created() {
    const ws_url = "ws://195.211.102.43:8999";
    this.connection = new WebSocket(ws_url);

    this.connection.onmessage = (e) => {
      console.log(e.data);
      if (e.data == "prt2_click") {
        console.log(e);
        this.showPort = true;
      }
      if (e.data == "noprt_click") {
        console.log(e);
        this.showPort = false;
      }
    };

    this.connection.onerror = (error) => {
      console.log(error);
    };
  },
  components: {
    BlockCircle,
    BlockGlobus,
    BlockRating,
    BlockDown,
    BlockScience,
    BlockFinance,
  },
};
</script>

<style lang="scss">
.layout-link {
  position: absolute;
  top: 2.188vw;
  left: 2.188vw;
  display: flex;
  align-items: center;
  margin: -0.781vw;
}

.layout-link__item {
  padding: 0.781vw;
}

.layout-link__router {
  position: relative;
  z-index: 1;
}

.cols {
  display: flex;
  height: 100%;
  padding-top: 5vw;
  padding-bottom: 8vw;
  position: relative;
}

.col {
  flex: 1;
  padding: 0 1.458vw;
}

.col--right {
  padding-top: 2.604vw;
}

.portrets__btn {
  position: absolute;
  top: 2.188vw;
  left: 13.188vw;
  width: 4.708vw;
  height: 2.708vw;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: center;
}

.portrets__btn svg {
  position: absolute;
  width: 4.708vw;
  height: 2.708vw;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
}

.portrets__btn-text {
  font-size: 0.82vw;
  color: #217aff;
}

.portret__box {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  height: 80vh;
  width: 27vw;
  z-index: 1000;
  -webkit-box-shadow: inset 0 0 100px #000;
  -moz-box-shadow: inset 0 0 100px #000;
  box-shadow: inset 0 0 100px #000;
}

.video {
  position: absolute;
  overflow: hidden;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 9;

  video {
    width: 100%;
    display: block;
    height: 100%;
    object-fit: cover;
  }
}

.portret__foto {
  height: 80vh;
  width: 27vw;
  top: 44% !important;
}

.portret__title {
  text-align: center;
  font-size: 3.45vh;
  line-height: 3.9vh;
  color: #1b1b1b;
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  top: 85% !important;
  z-index: 9;
}
</style>
