<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <NewTitle/>
    <NewJumbotron/>
  </div>
</template>

<script>
import NewTitle from './components/NewTitle.vue'
import NewJumbotron from './components/NewJumbotron.vue';

export default {
  name: 'App',
  components: {
    NewTitle,
    NewJumbotron
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
