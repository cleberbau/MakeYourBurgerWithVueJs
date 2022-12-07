<script setup>
import { RouterLink, RouterView } from 'vue-router'
import AboutViewVue from './views/AboutView.vue';
import HomeViewVue from './views/HomeView.vue';

</script>

<template>
  <header>
    
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>

</style>
