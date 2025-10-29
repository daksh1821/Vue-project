<script setup>
import { ref } from 'vue'
const props = defineProps(['first_name', 'last_name'])
console.log(props)
</script>

<template>
  <h1>{{ props.first_name }}</h1>
  <h1>{{ props.last_name }}</h1>
</template>
<style scoped></style>
