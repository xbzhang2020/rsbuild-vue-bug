<script lang="ts" setup>
import { ref } from "vue";
const count = ref(0);
</script>

<template>
  <div class="content">
    <h1>Rsbuild with Vue</h1>
    <p>Start building amazing things with Rsbuild.</p>

    <button @click="count++">+</button>
    <span>{{ count }}</span>
    <button @click="count--">-</button>
  </div>
</template>
