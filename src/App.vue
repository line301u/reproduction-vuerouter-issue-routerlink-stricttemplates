<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>

<template>
  <main>
    <RouterLink to="/" @focus="console.log('focus')">test</RouterLink>
  </main>
</template>
