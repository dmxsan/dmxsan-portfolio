<script setup lang="ts">
import { Analytics } from '@vercel/analytics/nuxt';
</script>

<template>
  <Analytics />
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
