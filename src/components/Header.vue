<template>
  <header class="header">
    <Hamburger />
    <Logo />
  </header>
</template>

<script>
import Logo from './Logo'
import Hamburger from './Hamburger'

export default {
  name: 'Header',
  props: {
    msg: String
  },
  components: {
    Logo,
    Hamburger
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  text-align: center;
}
</style>
