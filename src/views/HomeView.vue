<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="center">
    <RouterLink to="/main"
      ><img alt="homeLogo" class="logo" src="@/assets/face.logo.png"
    /></RouterLink>
  </div>
</template>

<style scoped>
.center {
  text-align: center;
}
.logo {
  width: 35%;
  height: 35%;
  margin-top: 2em;
  animation: fluffy1 3s ease infinite;
  filter: drop-shadow(3px 3px 5px #916632b3);
}
@keyframes fluffy1 {
  0% {
    transform: translateY(0);
  }
  5% {
    transform: translateY(0);
  }
  10% {
    transform: translateY(0);
  }
  20% {
    transform: translateY(-20px);
  }
  25% {
    transform: translateY(0);
  }
  30% {
    transform: translateY(-10px);
  }
  50% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(0);
  }
}

@media (min-width: 1024px) {
  .logo {
    margin-top: 2em;
  }
}
</style>
