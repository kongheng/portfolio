<template>
    <MyGreeting msg="Hello! Good to see you."></MyGreeting>
</template>

<script>
import MyGreeting from './components/Greeting.vue'

export default {
  name: 'App',
  components: {
    MyGreeting
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
