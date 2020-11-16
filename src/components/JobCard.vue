<template>
  <div>
     <b-col>
      <b-card
    :title="name"
    img-src= "@/assets/rovingo.jpg"
    img-alt="Image"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
        <b-card-text>
        a</b-card-text>
        <b-button variant="primary">Apply</b-button>
      </b-card>
      
    </b-col>
  </div>
</template>

<script>

export default {
  props: ["name"]
}
</script>