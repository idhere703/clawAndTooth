<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin:40px auto;
  max-width:650px;
  line-height:1.6;
  font-size:18px;
  color:#444;
  padding:0 10px
  }
  h1,h2,h3
  {
    line-height:1.2
  }
</style>
