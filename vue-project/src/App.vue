<script setup>
import { ref } from 'vue';
const first_name = ref("daksh");
const last_name = ref("jain");
import staticpropscomponents from './components/staticpropscomponents.vue';
import dynamicprops from './components/dynamicprops.vue';
</script>

<template>
  <staticpropscomponents name="daksh"/>
  <hr>
  <dynamicprops :first_name="first_name" :last_name="last_name"/>
</template>
