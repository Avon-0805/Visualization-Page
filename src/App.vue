<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Index from '@/views/index.vue'
</script>

<template>
  <Index />
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <!-- <RouterLink to="/about">About</RouterLink> -->
         嘿这里是
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}
</style>
