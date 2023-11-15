<template>
  <RouterView />
  <FooterNav />
</template>

<script setup>
import FooterNav from './components/FooterNav.vue';
import { RouterView, RouterLink } from 'vue-router';

</script>

<style scoped>
</style>