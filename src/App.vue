<script setup>
import MainButton  from './components/MainButton.vue';
const greeting = 'Hello world'
const blogPost = '<p style="color:red;">Ini adalah blogpost</p>'
const id = '1'
const blog = "text-center flex text-2xl"
</script>

<template>
  <MainButton/>
  <MainButton/>
  <MainButton/>
  <p>Guntur Lailam Yuro</p>
  <OptionsComponent/>
  <composition-component/>

  <div :id :class>
    {{ blogPost }}
  </div>
  <div v-html="blogPost"></div>
</template>

<style scoped>

</style>
