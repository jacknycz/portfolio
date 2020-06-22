<template>
  <svg id="" class="hamburger" xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 80 80">
    <g class="line line1">
      <rect width="80" height="15" fill="#fff" x="0" y="0" />
    </g>
    <g class="line line2">
      <rect width="80" height="15" fill="#fff" x="0" y="32.5" />
    </g>
    <g class="line line3">
      <rect width="80" height="15" fill="#fff" x="0" y="65" />
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
  margin-right: 40px;
  margin-top: 40px;
  transition: .3s ease-in-out all;

  &:hover {
    .line {
      transition: .3s ease-in-out all;
      transform-origin: center center;
    }
    .line1 {
      transform: translate(15px, 0) rotate(-45deg);
    }
    .line2 {
      transform: translate(15px, 0) rotate(180deg);
    }
    .line3 {
      transform: translate(15px, 0) rotate(45deg);
    }
  }
}
</style>
