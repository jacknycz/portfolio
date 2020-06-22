<template>
  <header class="header">
    <div class="row row-justify-flex-end">
      <Hamburger />
    </div>
    
    <div class="row row-justify-center">
      <Logo />
    </div>
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
  /* text-align: center; */
}
</style>
