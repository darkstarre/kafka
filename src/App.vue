<template>
  <div id="app">
    <img class="background-fade" src="./assets/kafka.jpg">
    <h1 class="title-app">Kafkanekt</h1>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  font-family: 'Roboto', sans-serif;
  font-family: 'Bangers', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.background-fade {
  opacity: 0.4;
}

.title-app {
  margin-top: -680px;
  color: orange;
  font-family: 'Bangers', cursive;
  line-height: 5px;
  font-size: 84px;
}
</style>
