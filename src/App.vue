<template>
  <div id="app">
    <Hero />
    
    <Img />

  </div>
</template>

<script>
import Hero from '@/components/hero.vue'
import Img from '@/components/jumbotron.vue'

export default {
  name: 'App',
  components: {

    Hero,
    Img,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
