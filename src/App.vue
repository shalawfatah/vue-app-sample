<template>
<div id="app">
{{user.name}}
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
    name: "Shalaw Fatah",
    firstName: "Shalaw",
    lastName: "Fatah",
    email: "shalaw.fatah@gmail.com",
    isAdmin: true
    }
     }
  }
  computed: {
  fullName() {
  return `${this.user.firstName} ${this.user.lastName} `
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
