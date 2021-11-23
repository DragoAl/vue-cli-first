<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyFirstApp msg="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>
import MyFirstApp from './components/Title.vue'

export default {
  name: 'App',
  components: {
    MyFirstApp
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

