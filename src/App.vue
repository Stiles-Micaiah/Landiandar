<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue';
</script>

<template>
  <div class="container-fluid">

    <img src="@/assets/blueriver.jpeg" class="card-img" alt="...">

    <RouterView />
  </div>
</template>

<style>
html,
body {
  margin: 0;
  padding: 0;
}
</style>