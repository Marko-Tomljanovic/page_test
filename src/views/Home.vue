<template>
  <b-container>
  <b-row align-center="center">
    <job-card></job-card>
    <job-card></job-card>
    <job-card></job-card>
    <job-card></job-card>

    <!-- <b-col md="3">
      <b-card title="This is a card" img-src="http://picsum.photos/400/300/?image=25" img-top style="max-width:20rem" class="mb-2">
        <b-card-text>
        Nesto tekt kao samo da proba ovo ono</b-card-text>
        <b-button variant="primary">Apply</b-button>
      </b-card>
    </b-col>


    <b-col md="3">
      <b-card title="This is a card" img-src="http://picsum.photos/400/300/?image=25" img-top style="max-width:20rem" class="mb-2">
        <b-card-text>
        Nesto tekt kao samo da proba ovo ono</b-card-text>
        <b-button variant="primary">Apply</b-button>
      </b-card>
    </b-col>


    <b-col md="3">
      <b-card title="This is a card" img-src="http://picsum.photos/400/300/?image=25" img-top style="max-width:20rem" class="mb-2">
        <b-card-text>
        Nesto tekt kao samo da proba ovo ono</b-card-text>
        <b-button variant="primary">Apply</b-button>
      </b-card>
    </b-col>


    <b-col md="3">
      <b-card title="This is a card" img-src="http://picsum.photos/400/300/?image=25" img-top style="max-width:20rem" class="mb-2">
        <b-card-text>
        Nesto tekt kao samo da proba ovo ono</b-card-text>
        <b-button variant="primary">Apply</b-button>
      </b-card>
    </b-col> -->
    
  </b-row>
</b-container>
</template>

<script>
// @ is an alias to /src
import JobCard from "@/components/JobCard.vue";

export default {
  name: 'Home',
  components: {"job-card": JobCard }
}
</script>
