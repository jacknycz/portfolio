<template>
  <svg id="" class="hamburger" xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 80 80">
  <g id="Rectangle_13" data-name="Rectangle 13" fill="#fff">
    <rect width="80" height="15" stroke="none"/>
    <rect x="0.5" y="0.5" width="79" height="14" fill="none"/>
  </g>
  <g id="Rectangle_14" data-name="Rectangle 14" transform="translate(0 33)" fill="#fff">
    <rect width="80" height="15" stroke="none"/>
    <rect x="0.5" y="0.5" width="79" height="14" fill="none"/>
  </g>
  <g id="Rectangle_15" data-name="Rectangle 15" transform="translate(0 65)" fill="#fff">
    <rect width="80" height="15" stroke="none"/>
    <rect x="0.5" y="0.5" width="79" height="14" fill="none"/>
  </g>
</svg>

</template>

<script>
export default {
  name: 'Hamburger',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.hamburger {
    rect {
      fill: black;
    }
}
</style>
