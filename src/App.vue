<template>
  <div style="background: #F0F8FF"> 
    
      <top-header></top-header>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    <br><br>
        <router-view/>
  </div>
</template>



<script>
import TopHeader from '@/components/TopHeader.vue';
export default {
  components:{
    'top-header': TopHeader

  }
}
</script>


