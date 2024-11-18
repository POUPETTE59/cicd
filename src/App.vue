<template>
  <div class="mainCtn">
    <NavBar/>
    <HeaderBrunch/>
    <CallToAction/>
   
  </div>
</template>

<script setup>
import NavBar from '@/components/NavBar.vue';
import HeaderBrunch from '@/components/HeaderBrunch.vue'
import CallToAction from './components/CallToAction.vue';

</script>

<style lang="scss"> 
@import url(https://fonts.googleapis.com/css2?family=Fredoka:wght@300..700&family=Roboto:wght@100;400&display=swap);
*{
  margin: 0;
  font-family: "roboto";
 }


 .mainCtn {
  background-color: #FDF4D1;

 }
 
</style>
