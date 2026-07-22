<script setup lang="ts"></script>

<template>
  <footer class="footer">
    <p>&#127279; 2026 - No copyright!</p>
  </footer>
</template>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  justify-content: flex-end;

  background-color: var(--the-footer-background);
  color: var(--the-footer-color);
  min-height: 10dvh;

  & > * {
    padding: 1rem;
  }
}
</style>
