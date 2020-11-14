<template>
  <b-container>
  <b-row align-center="center">
    <job-card v-for="job in jobs" :key="job.id"></job-card>
    

    
    
  </b-row>
</b-container>
</template>

<script>
// @ is an alias to /src
import JobCard from "@/components/JobCard.vue";

export default {
  name: 'home',
  components: {"job-card": JobCard },
  mounted(){
    this.fetchData();
  },
  data(){
    return {
      jobs: []

    };
  },
  methods:{
    async fetchData(){
      const res = await fetch("jobs.json");
      const val = await res.json();
      this.jobs = val; 
      console.log(val);

    }
  }
};
</script>
