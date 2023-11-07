<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './module/landing-page/components/HelloWorld.vue'
</script>

<template>
  <header>
    <div>
      <HelloWorld msg="Hello World" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
</style>
