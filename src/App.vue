<template>
  <nav class="level">
    <p class="level-item has-text-centered">
      <a class="link is-info">Home</a>
    </p>
    <p class="level-item has-text-centered">
      <a class="link is-info">Menu</a>
    </p>
    <p class="level-item has-text-centered">
      <img src="http://bulma.io/images/bulma-type.png" alt="" style="height: 30px;">
    </p>
    <p class="level-item has-text-centered">
      <a class="link is-info">Reservations</a>
    </p>
    <p class="level-item has-text-centered">
      <a class="link is-info">Contact</a>
    </p>
  </nav>
  Copy

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
}
</style>
