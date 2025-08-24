<template>
  <p v-for="text in dataList">{{ text }}</p>
</template>

<script setup>
const dataList = ["a", "b", "c", "d"];
</script>

<style scoped></style>
