<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import ModeToggle from './components/ModeToggle.vue'
</script>

<template>
  <header>
    <div class="container">
      <nav class="flex gap-4 h-14 items-center">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <ModeToggle />
      </nav>
    </div>
  </header>

  <RouterView />
</template>
