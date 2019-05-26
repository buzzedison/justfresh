<template>
 <div>
   
     <v-toolbar color="orange">
   
    <v-toolbar-title>Just Fresh</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat>Home</v-btn>
      <v-btn flat>About</v-btn>
      <v-btn flat>Food</v-btn>
      <v-btn flat>Insight</v-btn>
      <v-btn flat>Juices</v-btn>
    </v-toolbar-items>
  </v-toolbar>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.v-btn {
  color:white;
  font-family: roboto;
  font-size: 18px;
}
</style>
