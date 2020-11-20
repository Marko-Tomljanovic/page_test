<template>
<div>
  <b-navbar toggleable="lg" type="dark" variant="#E6E6FA" >
    <b-navbar-brand style="font-size: 26px; color: #306b8e" to="/"><cube></cube></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav style="font-size: 20px">
         <b-nav-item to="/education"><a style="color: #306b8e">Education</a> </b-nav-item>
        <b-nav-item to="/features"><a style="color: #306b8e">Features</a> </b-nav-item>
        <b-nav-item to="/jonson"><a style="color: #306b8e">json</a> </b-nav-item>
        
      </b-navbar-nav>
    </b-collapse>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav style="font-size: 20px">
         <b-nav-item to="/education"><a style="color: #306b8e">Education</a> </b-nav-item>
        <b-nav-item to="/features"><a style="color: #306b8e">Features</a> </b-nav-item>
        <b-nav-item to="/jonson"><a style="color: #306b8e">json</a> </b-nav-item>
        
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>


<script>
import rotateCube from './../components/rotateCube.vue';
export default {
  components:{
    'cube': rotateCube

  }
}
</script>  
