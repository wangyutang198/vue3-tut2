<template>
  <h1>Computed計算屬性</h1>

  <h3>{{ numFormat }}</h3>
</template>

<script setup>
import { computed } from "vue";
const num = 0.5;

const numFormat = computed(() => {
  if (Number.isNaN(num * 100)) return num;
  return `${num * 100}%`;
});
</script>

<style scoped></style>

