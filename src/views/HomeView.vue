<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <p>{{ count }}</p>
  </div>
</template>
<script setup lang="ts">
import { ref } from "vue";
const count = ref(0);
</script>
