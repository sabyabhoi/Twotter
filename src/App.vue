<template>
<div id="app">
{{ user.username }}
</div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      followers: 0,
      user: {
        id: 1,
        username: 'sabyabhoi',
        firstName: 'Sabyasachi',
        lastName: 'Bhoi',
        email: 'sabyabhoi@gmail.com',
        isAdmin: true
      }
    }
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
