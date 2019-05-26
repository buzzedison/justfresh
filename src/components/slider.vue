<template>
<div>
<b-container fluid class="bv-example-row">
  <b-row class="slider">
    <b-col>
<div class="jumbotron">
  <b-jumbotron>
    <template slot="header">Food, Juices, Catering, Consulting</template>

    <template slot="lead">
     We have been serving healthy food, awesome smoothies, and the best juices in town since 2013. We do events, we can help 
     you setup your new food business with our rich experience. 
    </template>

    <hr class="my-4">

    

    <b-button variant="dark" href="#">See Menu</b-button>
    <b-button variant="danger" href="#">Start a food business</b-button>
  </b-jumbotron>
</div>

    </b-col>
    <b-col>

         <v-img
       :src="require('../assets/images/people.jpg')"
       max-height ="550px"
      />
    </b-col>
   
  </b-row>
</b-container>
    </div>
</template>


<script>
export default {
    name:'Slider'
}
</script>



<style scoped>
.slider{
    max-width: 120%;
    background-color:orangered;
    height: 550px;
    
  
}

.jumbotron{
    background-color: transparent;
    color:white;
}

</style>