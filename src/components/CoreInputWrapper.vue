<template>
  <core-input>
    <template v-for="(_, slot) of $slots" :key="slot" #[slot]="scope">
      <slot :key="slot" :name="slot" v-bind="scope" />
    </template>
  </core-input>
</template>
<script setup lang="ts">
import CoreInput from './CoreInput.vue'
</script>
