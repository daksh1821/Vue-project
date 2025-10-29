<script setup>
import { ref ,onBeforeMount ,onBeforeUpdate,onMounted, onUpdated, onBeforeUnmount, onUnmounted} from 'vue';
const messege = ref("hello");
</script>

<template>
<p>{{messege}}</p>
</template>
