<template>
  <NuxtPage />
  <AuthOverlay v-if="isLoginOpen"/>
</template>
<script setup>

import { storeToRefs } from 'pinia';
const { $userStore, $generalStore } = useNuxtApp()
const { isLoginOpen, isEditProfileOpen } = storeToRefs($generalStore)
</script>