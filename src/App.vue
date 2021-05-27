<template>
  <div id="app">
    <h1>Invite</h1>
    <a href="https://discord.com/api/oauth2/authorize?client_id=837687420107227186&permissions=0&scope=bot">Invite here!</a>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {},
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
  h1 {
    color: white;
  }
  a {
    color: aqua;
  }
  body {
    background-color: black;
  }
}
</style>
