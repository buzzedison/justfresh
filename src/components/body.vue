<template>
<div>
      <b-container class="bv-example-row">
  <b-row class="w-100">
    <b-col><v-flex>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="600"
    >
      <v-img
        :aspect-ratio="16/9"
        :src="require('../assets/images/food.jpg')"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            from GHC 25
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>
        <div class="font-weight-light grey--text title mb-2">Check out our food options</div>
        <h3 class="display-1 font-weight-light orange--text mb-2">Breakfast & Lunch</h3>
        <div class="font-weight-light title mb-2">
          Are you hungry? Click to order food.
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
</v-flex>
</b-col>
    <b-col><v-flex>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="600"
    >
      <v-img
        :aspect-ratio="16/9"
        :src="require('../assets/images/juice.jpg')"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out orange darken-2 v-card--reveal display-3 white--text"
            style="height: 100%;"
          >
            from GHC 5
          </div>
        </v-expand-transition>
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>
        <div class="font-weight-light grey--text title mb-2">Get healthy Juices and Smoothies</div>
        <h3 class="display-1 font-weight-light orange--text mb-2">Best juices and smoothies</h3>
        <div class="font-weight-light title mb-2">
          Everything is fresh
        </div>
      </v-card-text>
    </v-card>
  </v-hover>
</v-flex></b-col>
   
  </b-row>
</b-container>


</div>

</template>


<script>

export default {
    name: 'Body'
}

</script>


<style>
.v-card--reveal {
  align-items: center;
  bottom: 0;
  
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%;
}

.bv-example-row{
    padding-top: 0px;
}
</style>
