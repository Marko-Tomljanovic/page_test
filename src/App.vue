<template>
  <div style="background-color: #E6E6FA"> 
    
      <top-header></top-header><br>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
      <transition name="fade">
        <router-view/><br>
      </transition>
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



<style scoped>
.fade-enter-active, .fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from, .fade-leave-to {
  opacity: 0;
}
</style>



