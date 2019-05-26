<template>
  <div id="app">
   
    <Main/>
    <Intro/>
  </div>
</template>

<script>
import Main from './components/main.vue'
import Intro from './components/intro.vue'
export default {
  name: 'app',
  components: {
    Main,
    Intro
    
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
  margin-top: 0px;
}
</style>
