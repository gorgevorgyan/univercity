  <template>
  <div class="line" :class="{'line--red': progress_red,'line--37':line_37,'line--78':line_78,'line--42':line_42}"></div>
  </template>

  <script>
  export default {
  name: "ProgressSecond",
  data() {
  return {

  }
  },

  props: {
    progress_red: {
      type: Boolean,
      default: false
    },
    line_37:{
      type:Boolean,
      default:false
    },
    line_78:{
      type:Boolean,
      default:false
    },
    line_42:{
      type:Boolean,
      default:false
    }

  }
  }
  </script>

  <style lang="scss" scoped>
  .line {
  background-color: #FB9B2B;
  height: 6px;
  width: 10%;
  position: relative;
  &:before {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 0 6px 6px;
  border-color: transparent transparent #101f54 transparent;
  }
  }

  .line--red {
  background-color: #FF5A5A;
  }
  .line--37{
  width: 37%;
  } 
  .line--78{
  width: 78%;
  }
  .line--42{
  width: 42%;
  }
  </style>