<script setup>
import { RouterView } from "vue-router";
import Navbar from './components/layouts/Navbar.vue';
</script>

<template>
  <Navbar />
  <RouterView />
</template>

<style>
@import url(@/assets/css/styles.css);
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
</style>
