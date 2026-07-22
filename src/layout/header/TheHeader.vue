<script setup lang="ts">
import NavbarButton from '@/layout/header/NavbarButton.vue'
import TheLogo from '@/components/TheLogo.vue'
</script>

<template>
  <header class="header">
    <TheLogo />
    <NavbarButton />
  </header>
</template>

<style scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;

  background-color: var(--background-color);
  min-height: 5.5rem;
  padding: 1.25rem;
}
</style>
