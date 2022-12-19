<template>
  <div id="app">
    <core-input-wrapper>
      <template #before> bofore slot </template>
      <template #after> after slot </template>
    </core-input-wrapper>
  </div>
</template>

<script setup>
import CoreInputWrapper from './components/CoreInputWrapper.vue'
</script>
