<script setup lang="ts">
</script>

<template>
   <div class="row">
      <div class="item" v-for="index in 4">
         <img src="../public/小罗伯特唐尼 - 副本.jpg" alt="">
         <div class="img-name">
            小罗伯特唐尼 - 副本
         </div>
      </div>
   </div>
</template>

<style scoped>
.row {
   height: 500px;
   width: 100%;
   color: white;
   display: flex;
   flex-wrap: wrap;
   justify-content: space-around;
}

.item {
   background-color: gray;
   width: 26%;
   height: 150px;
}

/* 如果最后一行是一个元素 */
.item:last-child:nth-child(3n-1) {
   margin-right: calc(32.5% + 3% / 3);
}

/* 如果最后一行是2个元素 */
.item:last-child:nth-child(3n - 2) {
   margin-right: calc(65% + 6% / 3);
}

img {
   width: 100%;
   height: 60%;
}

.img-name {
   width: 100%;
   height: 33%;
   /* padding: 0 10px; */
   font-size: 10px;
   text-align: center;
   /* 多行文本溢出解决方案 */
   display: -webkit-box !important;
   overflow: hidden;
   word-break: break-all;
   text-overflow: ellipsis;
   -webkit-box-orient: vertical;
   -webkit-line-clamp: 3;
}
</style>
