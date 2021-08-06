<template>
  
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <TicTacToc/>
</template>

<script>

import TicTacToc from './components/index.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap-vue/dist/bootstrap-vue.css"

export default {
  name: 'App',
  components: {
    TicTacToc,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
