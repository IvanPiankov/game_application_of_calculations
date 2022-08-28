<template>
  <main>
<!--    <TheWelcome />-->
  <nav>
    <RouterLink to="/">Settings</RouterLink>
  </nav>
  </main>
  <RouterView />
</template>

<script setup>
// import TheWelcome from '@/components/TheWelcome.vue'
import { RouterLink, RouterView } from 'vue-router'
</script>

<style>
/*@media (min-width: 1024px) {*/
/*  .about {*/
/*    min-height: 100vh;*/
/*    display: flex;*/
/*    align-items: center;*/
/*  }*/
/*}*/
</style>