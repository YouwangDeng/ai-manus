<template>
  <div className="h-screen flex overflow-hidden bg-white">
    <div className="flex-1 min-w-0 h-full py-0 pr-0 relative">
      <div className="flex h-full bg-[var(--background-gray-main)]">
        <router-view />
      </div>
    </div>
  </div>
  <Toast />
</template>

<script setup lang="ts">
import Toast from './components/Toast.vue';
</script>
