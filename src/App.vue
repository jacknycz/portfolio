<template>
  <div id="app">
    <Header />
    <Intro msg="Jack Nycz"/>
  </div>
</template>

<script>
import Intro from './components/Intro.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Intro,
    Header
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200;300;400;500;523;600;700;800&display=swap');

body {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Manrope', sans-serif;
  font-size: 16px;
}
</style>
