<template>
<div>
    <b-container class="bv-example-row">
  <b-row>
    <b-col>1 of 3</b-col>
    <b-col>2 of 3</b-col>
    <b-col>3 of 3</b-col>
  </b-row>
</b-container>
 <v-container grid-list-md text-xs-center fluid>
    <v-layout row wrap>
      <v-flex xs12>
        <v-card>
          <v-card-text class="px-0"> <v-layout>
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-img fluid
          class="white--text"
          height="400px"
          width ="950"
          src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
        >
         
        </v-img>
       
       
      </v-card>
    </v-flex>
  </v-layout></v-card-text>
        </v-card>
      </v-flex>
      
    </v-layout>
    
  </v-container>

</div>


</template>




<script>

export default {
    name: 'Intro'
}


</script>



<style>


</style>