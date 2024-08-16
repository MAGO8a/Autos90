<script setup>
import Head from '@/components/Head.vue'
import Card from '@/components/Card.vue';
import Card2 from '@/components/Card2.vue';
import Slogan from '@/components/Slogan.vue';
</script>

<template>
  <div class="app-container">
    <Head/>
    <Card/>
    <Slogan/>
    <Card2/>
  </div>
</template>

<style scoped>
.app-container {
  width: 100%;
  min-height: 100%; 
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial,
    sans-serif;
  background-image: url(../assets/gradient-blue-abstract-background-smooth-dark-blue-with-black-vignette-studio.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;  
}
</style>
