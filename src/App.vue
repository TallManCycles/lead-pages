<script setup lang="ts">
import { RouterView } from 'vue-router'
import './assets/main.css'
</script>

<template>
  <RouterView />
</template>

<style>
@import '@fortawesome/fontawesome-free/css/all.css';
@tailwind base;
@tailwind components;
@tailwind utilities;

body {
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
}
</style>
