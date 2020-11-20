<template>
  <div style="background-color: #E6E6FA"> 
    
      <top-header></top-header><br>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
        <router-view/><br>
        <bootom></bootom>
  </div>
</template>



<script>
import TopHeader from '@/components/TopHeader.vue';
import Bootom from '@/components/Bootom.vue';
export default {
  name: 'app',
  components:{
    
    'top-header': TopHeader,
    'bootom': Bootom


  }
}
</script>



