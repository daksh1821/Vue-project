<script setup>
import { reactive } from 'vue';
let initial_state = reactive({val: {count:0}, user:["daksh", "jain"]});
const changeuser = () =>{
  initial_state.user[0] = "khushi";
  initial_state.user[1] = "pathak";
}
</script>

<template>
<h1>Count : {{initial_state.val.count}}</h1>
<h1>users: {{initial_state.user}}</h1>
<button @:click="initial_state.val.count++">Increment</button>
<button @:click="changeuser"> change user</button>
</template>

<style scoped></style>
