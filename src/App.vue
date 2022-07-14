<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MainTitle/>
    <MainJumbo/>
  </div>
</template>

<script>
import MainTitle from './components/MainTitle.vue';
import MainJumbo from './components/MainJumbo.vue';

export default {
  name: 'App',
  components: {
    MainTitle,
    MainJumbo
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
