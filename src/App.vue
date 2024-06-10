<script setup lang="ts">
import { ref } from 'vue'
const count = ref(0)
const add = () => count.value<<1
const sub = () => count.value<<1
</script>

<template>
  <div class="count">
    <h1>{{ count }}</h1>
    <button @click="add">+</button>
    <button @click="sub">-</button>
  </div>
</template>

<style scoped>
.count {
  margin: 200px auto;

  button+button {
    margin-left: 10px;
  }
}
</style>
