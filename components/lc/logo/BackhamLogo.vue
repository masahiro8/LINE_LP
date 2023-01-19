<script setup lang="ts">
import { ref } from "vue";
import BackhamLogo from "/images/logos/backham.png";
</script>

<template>
  <NuxtLink to="/" class="d-flex">
    <img :src="BackhamLogo" alt="logo" />
  </NuxtLink>
</template>

<style scoped>
img {
  width: 72px;
}
</style>
