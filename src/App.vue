<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <main class="yellow">
    <RouterView />
  </main>

  <footer>
    <p>Copyright</p>
  </footer>
</template>

<style scoped>
.yellow {
  background-color: rgb(255, 147, 185);
}
footer {
  background-color: rgba(255, 255, 255, 0.537);
  text-align: center;
}
@media (min-width: 1024px) {
}
</style>
