<template>
  <div id="app">
   
    <Main/>
   
    <Body/>
    <Section/>
  </div>
</template>

<script>
import Main from './components/main.vue'

import Body from './components/body'
import Section from './components/section'
export default {
  name: 'app',
  components: {
    Main,
    Body,
    Section
    
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
