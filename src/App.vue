<template>
  <div id="app">
   
    <Main/>
   <Slider/>
   <Section/>
    <Body/>
    
  </div>
</template>

<script>
import Main from './components/main.vue'

import Body from './components/body'
import Section from './components/section'
import Slider from './components/slider'
export default {
  name: 'app',
  components: {
    Main,
    Section,
    Body,
    Slider
    
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Noto+Sans|Oswald&display=swap');
#app {
  font-family: 'Noto Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
  margin-top: 0px;
}
</style>
