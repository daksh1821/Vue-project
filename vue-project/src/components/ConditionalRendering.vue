<script setup>
import { ref } from 'vue';
const isVisible1 = ref(true);
const isVisible2 = ref(false);
</script>

<template>
<p v-if="isVisible2">hiiiii......</p>
</template>

<style scoped></style>
