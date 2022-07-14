<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MainTitle />
    <MainHero />
  </div>
</template>

<script>
import MainTitle from './components/Title.vue'
import MainHero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    MainTitle,
    MainHero,
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
