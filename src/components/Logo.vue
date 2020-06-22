<template>
  <div class="logo">
      <svg id="logo" data-name="Component 6 – 1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="139.999" height="115.004" viewBox="0 0 139.999 115.004">
  <defs>
    <linearGradient id="logo-gradient" x1="0.5" x2="0.5" y2="1" gradientUnits="objectBoundingBox">
      <stop offset="0" stop-color="#f8971b"/>
      <stop offset="1" stop-color="#9b391a"/>
    </linearGradient>

    <linearGradient id="logo-gradient-hover" x1="0.5" x2="0.5" y2="1" gradientUnits="objectBoundingBox">
      <stop offset="0" stop-color="#9b391a"/>
      <stop offset="1" stop-color="#f8971b"/>
    </linearGradient>
  </defs>
  <path class="j" id="Union_2" data-name="Union 2" d="M-773.569-13018.142a39.969,39.969,0,0,1-12.715-8.571,39.93,39.93,0,0,1-8.571-12.719A39.719,39.719,0,0,1-798-13055h20a19.852,19.852,0,0,0,5.865,14.134A19.859,19.859,0,0,0-758-13035a20.023,20.023,0,0,0,20-20v-30h20v30a39.789,39.789,0,0,1-3.139,15.565,39.887,39.887,0,0,1-8.574,12.719,39.883,39.883,0,0,1-12.715,8.571A39.763,39.763,0,0,1-758-13015,39.759,39.759,0,0,1-773.569-13018.142Z" transform="translate(797.998 13130)"/>
  <path class="n" id="Union_1" data-name="Union 1" d="M-738-12970v-75h20v75Zm0-75a19.852,19.852,0,0,0-5.865-14.134A19.859,19.859,0,0,0-758-13065a20.023,20.023,0,0,0-20,20h-20a39.793,39.793,0,0,1,3.139-15.566,39.86,39.86,0,0,1,8.574-12.718,39.872,39.872,0,0,1,12.715-8.571A39.764,39.764,0,0,1-758-13085a39.76,39.76,0,0,1,15.569,3.146,39.841,39.841,0,0,1,12.715,8.571,39.938,39.938,0,0,1,8.571,12.718A39.717,39.717,0,0,1-718-13045Z" transform="translate(857.998 13085.002)"/>
</svg>
  </div>
</template>

<script>
export default {
  name: 'Logo',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.logo {
    display: block;
    text-align: center;

    .j, .n {
      fill: url(#logo-gradient);
      transition: .3s ease-in-out all;
    }

    &:hover {
      .j, .n {
        fill: url(#logo-gradient-hover);
      }
    }
}
</style>
