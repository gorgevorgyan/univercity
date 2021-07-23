<template>
  <div class="progress">
    <p class="progress__text">{{ progress }}</p>

    <svg
      width="5.208vw"
      height="0.625vw"
      viewBox="0 0 100 12"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
      class="progress__icon"
    >
      <path d="M4.5 0H0.5L11.5 12H15.5L4.5 0Z" fill="#FB9B2B"></path>
      <path d="M10.5 0H6.5L17.5 12H21.5L10.5 0Z" fill="#FB9B2B"></path>
      <path d="M16.5 0H12.5L23.5 12H27.5L16.5 0Z" fill="#FB9B2B"></path>
      <path d="M22.5 0H18.5L29.5 12H33.5L22.5 0Z" fill="#FB9B2B"></path>
      <path d="M28.5 0H24.5L35.5 12H39.5L28.5 0Z" fill="#FB9B2B"></path>
      <path d="M34.5 0H30.5L41.5 12H45.5L34.5 0Z" fill="#FB9B2B"></path>
      <path d="M40.5 0H36.5L47.5 12H51.5L40.5 0Z" fill="#FB9B2B"></path>
      <path d="M46.5 0H42.5L53.5 12H57.5L46.5 0Z" fill="#FB9B2B"></path>
      <path d="M52.5 0H48.5L59.5 12H63.5L52.5 0Z" fill="#FB9B2B"></path>
      <path d="M58.5 0H54.5L65.5 12H69.5L58.5 0Z" fill="rgba(251, 155, 43, 0.2)"></path>
      <path d="M64.5 0H60.5L71.5 12H75.5L64.5 0Z" fill="rgba(251, 155, 43, 0.2)"></path>
      <path
        d="M70.5 0H66.5L77.5 12H81.5L70.5 0Z"
        fill="rgba(251, 155, 43, 0.2)"
      ></path>
      <path
        d="M76.5 0H72.5L83.5 12H87.5L76.5 0Z"
        fill="rgba(251, 155, 43, 0.2)"
      ></path>
      <path
        d="M82.5 0H78.5L89.5 12H93.5L82.5 0Z"
        fill="rgba(251, 155, 43, 0.2)"
      ></path>
      <path
        d="M88.5 0H84.5L95.5 12H99.5L88.5 0Z"
        fill="rgba(251, 155, 43, 0.2)"
      ></path>
    </svg>
  </div>
</template>

<script>
export default {
  name: "Progress",
  props: ["progress"],
};
</script>

<style lang="scss">
.progress {
  position: absolute;
  z-index: 1;
}

.progress__text {
  font-weight: 700;
  font-size: 0.521vw;
  line-height: 1.042vw;
  color: #fb9b2b;
  padding-right: 0.5vw;
}
</style>
