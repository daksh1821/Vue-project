<script setup>
import { ref } from 'vue';
let count = ref(0);
const inc = () =>{
  count.value++;
}
</script>

<template>
<h1>Count : {{count}}</h1> 
<button @:click="inc">Increment</button>
</template>

<style scoped></style>
