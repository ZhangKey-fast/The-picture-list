<script setup lang="ts">
import Title from './components/Title.vue'
import PictureItem from './components/Picture-row.vue'
import Track from './components/Track.vue'
</script>

<template>
   <div class="container">
      <Title />
      <picture-item />
      <Track />
   </div>
</template>

<style>
.container {
   background-color: rgb(24, 15, 80);
   width: 400px;
   height: 700px;
   margin: 0 auto;
}
</style>
