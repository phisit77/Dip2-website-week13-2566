<template>
  <div>
    <router-link :to="{ name: 'home' }">Home</router-link> |
    <router-link :to="{ name: 'about' }">About</router-link>
  </div>
  <router-view />
</template>

<script setup>
</script>

<style lang="scss" scoped></style>