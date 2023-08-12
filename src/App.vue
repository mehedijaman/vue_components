<script setup>
import data from './data/data'
import PlacesToVisit from './components/PlacesToVisit.vue';
</script>

<template>
  <section class="mx-auto ">
    <h1 class="my-10 text-center">Components</h1>
    <div class="flex flex-col space-y-5">
     
      <PlacesToVisit 
      v-for= "(place, index) in data"
      :key=index 
      :place = place
      />
    </div>

  </section>
</template>

<style scoped></style>
