<template>
<div class="mojstil">
  <b-navbar toggleable="lg" >
    <b-navbar-brand style="font-size: 26px;" to="/"><cube></cube></b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse style="margin-left:32%;"   id="nav-collapse" is-nav>
      <b-navbar-nav style="font-size: 26px;">
        <b-nav-item class="sjena"  to="/"><a style="color:#ffffff;">Profile</a> </b-nav-item>
         <b-nav-item class="sjena" to="/education"><a style="color:#ffffff">Education</a> </b-nav-item>
        <b-nav-item to="/contactMe"><a>Contact Me</a> </b-nav-item>
        <b-nav-item to="/jonson"><a style="color: #ffffff">json</a> </b-nav-item>
      </b-navbar-nav>
    </b-collapse>

    <b-navbar-brand style="font-size: 26px;" to="/"><cube></cube></b-navbar-brand>

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


<style scoped>
  a {
  position: relative;
  display: inline-block;
  overflow: hidden;
   background: linear-gradient(to right,  #000000, #000000 50%, #ffffff 50%);
   background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-size: 200% 100%;
  background-position: 100%;
  transition: background-position 0.4s ease;
}
a:hover {
  background-position: 0 100%;
}
</style>