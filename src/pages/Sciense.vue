<template>
	<main class="layout">
    	<div class="btn_bg" v-on:click="bg_click" v-if="showSciense==0">
			<svg width="52" height="52" viewBox="0 0 52 52" fill="none" xmlns="http://www.w3.org/2000/svg" class="test">
				<path d="M51.5 38V38.2071L51.3536 38.3536L38.3536 51.3536L38.2071 51.5H38H1H0.5V51V11V10.7929L0.646446 10.6464L10.6464 0.646447L10.7929 0.5H11H51H51.5V1V38Z" stroke="#217AFF" stroke-opacity="0.4"/>
				<path d="M32.6657 17C35.2923 18.9086 37 22.0048 37 25.5C37 31.299 32.299 36 26.5 36C20.701 36 16 31.299 16 25.5C16 22.0048 17.7077 18.9086 20.3343 17" stroke="#217AFF" stroke-width="2"/>
				<path d="M26.5 13V27" stroke="#217AFF" stroke-width="2"/>
			</svg>
		</div>
    
    <img v-if="showSciense==0" @click="handler" src="/img/ph.jpg" alt="" class="test-img" width="100%">
    <img v-if="showSciense==1" @click="handler" src="/img/science.svg" alt=""   class="test-img" width="100%">
    <img v-if="showSciense==2" @click="handler" src="/img/finance.svg" alt="" class="test-img" width="100%">
    <img v-if="showSciense==4" @click="handler" src="/img/staff.svg" alt=""  class="test-img" width="100%">
    <img v-if="showSciense==5" @click="handler" src="/img/students.svg" alt=""  class="test-img" width="100%">
    <img v-if="showSciense==7" @click="handler" src="/img/group232.svg" alt=""  class="test-img" width="100%">
    
     <div v-if="showSciense==3 || (showSciense ==0 && activeBg )" class="video">
      <video autoplay="" loop="" muted="" playsinline="">
          <source src="../assets/img/video.mp4" type="video/mp4; codecs=&quot;avc1.42E01E, mp4a.40.2&quot;">
          Тег video не поддерживается вашим браузером.
      </video>
    </div>

    .
    
    <img v-if="showSciense==3" @click="handler" :src="urlImg" alt="" class="test-img" height="95%" width="auto">
   
     <div class="video"  v-if="showSciense==6">
      <video autoplay="" loop="" muted="" playsinline="">
        <source
          src="../assets/img/video.mp4"
          type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'
        />
        Тег video не поддерживается вашим браузером.
      </video>
    </div>
    <img v-if="showSciense==6"
      @click="handler"
      :src="urlImg2"
      alt=""
      class="test-img portret__foto"
      height="95%"
      width="auto"
    />
     
    <div class="portret__title" v-if="showSciense==6">
      Георгий Валентинович Плеханов<br />Философ<br />1856 - 1918 гг.
    </div>
    
    
	</main>
</template>

<script>
export default {
    
    
	name: 'Sciense',
  data() {
    return {
      showSciense:0,
      activeGif: false,
      activeBg: false,
      urlImg: "/img/gif1.png",  
      urlImg2: "/img/gif2.png"  
    }
  },
	components: {
	},
  methods: {
   handler() {
      this.activeGif = !this.activeGif

      if (this.activeGif) {
        this.urlImg = "/img/gif1.gif";
        this.urlImg2 = "/img/gif2.gif";
      } else {
        this.urlImg = "/img/gif1.png";
        this.urlImg2 = "/img/gif2.png";
      }
    },
    
    bg_click() {
        this.activeBg = !this.activeBg;
    }
    
  },
  created() {
     
        const ws_url = 'ws://195.211.102.43:8999'
        this.connection = new WebSocket(ws_url)
        
        this.connection.onerror = (error) => {
          console.log(error)
        }

        this.connection.onmessage = (e) => {
          console.log(e.data)
          if (e.data =="sc_click")
          {
              console.log(e);
              this.showSciense = 1;
          }
          if (e.data =="r_click" || e.data =="back_click")
          {
              console.log(e);
              this.showSciense = 0;
          }
            if (e.data =="fin_click")
          {
              
              this.showSciense = 2;
          }
          
             if (e.data =="prt_click")
          {
              this.showSciense = 3;
          }
          
             if (e.data =="prt2_click")
          {
              this.showSciense = 6;
          }
          
             if (e.data =="memb_click")
          {
              this.showSciense = 4;
          }
          
          if (e.data =="stud_click")
          {
              this.showSciense = 5;
          }
          
            if (e.data =="cr1_click")
          {
              this.showSciense = 7;
          }
          
              
        }
     
        
  },
}
</script>

<style lang="scss">


.btn_bg {
    z-index: 999;
    cursor: pointer;
}

.test {
	position: absolute;
	left: 45px;
	top: 45px;
	cursor: pointer;
  z-index: 999;
}

.test-img {
  z-index: 998;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
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
</style>
