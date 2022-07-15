<script setup>
import TimeShaft from './TimeShaft.vue'
import Pathway from './Pathway.vue';
</script>

<template>
   <div class="container">
      <TimeShaft />
      <Pathway />
   </div>
</template>

<style scoped>
.container {
   background-color: #fff;
   position: fixed;
   bottom: 0;
   height: 200px;
}
</style>
