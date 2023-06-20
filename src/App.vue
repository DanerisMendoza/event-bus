<template>
  <HelloWorld/>
  <SecondPage/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SecondPage from './components/SecondPage.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,SecondPage
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
