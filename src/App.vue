<script setup>
import { RouterView } from 'vue-router'
import HeaderComponent from './components/HeaderComponent.vue'
</script>

<template>
  <header>
    <HeaderComponent />
  </header>

  <RouterView />
</template>

<style scoped>
.certified-brand {
  background-color: #cca65b;
}
.nav-link {
  color: #3d4b4a !important;
}
.navbar-brand {
  font-size: 17px;
}
.join-us {
  background-color: black;
  color: whitesmoke;
  font-size: 15px;
  border-radius: 0;
  line-height: -0.5;
}
</style>
