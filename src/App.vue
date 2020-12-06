<template>
  <div> 
    
      <top-header></top-header><br>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
      <transition name="fade">
        <router-view/><br>
      </transition><br>
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



<style>
body{
  background-color: #2677a7;
}
.fade-enter-active, .fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from, .fade-leave-to {
  opacity: 0;
}
.mojstil{
  color: #ffffff;
  font-family: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif;
}

</style>



