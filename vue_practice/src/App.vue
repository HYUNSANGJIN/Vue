<template>
<!-- 여기선 html 짜고 -->
  <img alt="Vue logo" src="./assets/logo.png">
  안녕하세요
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
// 여기선 JS 짜고
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  /* 여기선 css 짜고 */
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
