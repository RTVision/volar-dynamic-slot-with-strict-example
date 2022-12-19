<template>
  <div id="app">
    <core-input-wrapper>
      <template #before> before slot </template>
      <template #after> after slot </template>
    </core-input-wrapper>
  </div>
</template>

<script setup lang="ts">
import CoreInputWrapper from '@/components/CoreInputWrapper.vue'
</script>
