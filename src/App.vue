<template>
    <CustomHeader></CustomHeader>
    <HelloWorld msg="Hello! Good to see you."/>
    <CustomFooter></CustomFooter>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CustomHeader from './components/Header.vue'
import CustomFooter from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    CustomHeader,
    CustomFooter
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
