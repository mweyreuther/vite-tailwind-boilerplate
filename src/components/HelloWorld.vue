<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>
  <p class="text-red-500 text-2xl">Hi there</p>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
