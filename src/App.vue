<script setup lang="ts"></script>

<template>
  <div>
    <RouterView />
    <div style="display: flex; gap: 1rem">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </div>
  </div>
</template>
