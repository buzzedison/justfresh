<template>
 <div>
   
  <b-navbar class="mainNav" toggleable="lg">
    <b-navbar-brand href="#">Just Fresh</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item class="navitem" href="#">Home</b-nav-item>
         <b-nav-item class="navitem" href="#">About</b-nav-item>
          <b-nav-item class="navitem" href="#">Food</b-nav-item>
           <b-nav-item class="navitem" href="#">Juices</b-nav-item>
            <b-nav-item class="navitem" href="#">Insight</b-nav-item>
             <b-nav-item class="navitem" href="#">Services</b-nav-item>
              <b-nav-item class="navitem" href="#">Contact</b-nav-item>
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>

       

        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template slot="button-content"><em>User</em></template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>


    
   
    
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
<style>
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

.navitem{
  color:black;
  font-weight:bold;
}







.ml-auto {
  color:rgb(248, 184, 8);
  
  font-size: 18px;
}

.mainNav{
  background-color: transparent;
  
  padding-top: 0px;
}


</style>
