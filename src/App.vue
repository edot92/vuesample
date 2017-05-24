<template>
  <div id="app">
    <img src="./assets/logo.png">
    <ul>
      <li>
        <router-link to="/hello">home</router-link>
      </li>
      <li>
        <router-link to="/home">HOME</router-link>
      </li>
    </ul>
    <br>
    <router-view></router-view>
  </div>

</template>
<script>
  export default {
    template: 'app'

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
  }
</style>
