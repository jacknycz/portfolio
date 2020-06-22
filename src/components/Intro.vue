<template>
  <div class="intro">
    <h1>{{ msg }}</h1>
    <h2>hey guys! I'm Jack Nycz and I'm a dude from Atlanta, Georgia who does UI/UX things</h2>
    <More />
  </div>
</template>

<script>

import More from './More'

export default {
  name: 'Intro',
  props: {
    msg: String
  },
  components: {
    More
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.intro {
  text-align: center;
  color: #fff;
}
</style>
