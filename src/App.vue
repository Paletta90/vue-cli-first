<template>
  <div id="app">
    <TitleBoolean/>
    <HeroBoolean/>
  </div>
</template>

<script>
import TitleBoolean from './components/TitleBoolean.vue'
import HeroBoolean from './components/HeroBoolean.vue'

export default {
  name: 'App',
  components: {
    TitleBoolean,
    HeroBoolean
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
