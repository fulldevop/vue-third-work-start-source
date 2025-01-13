<template>
  <div>
    <button> - </button>
    <span> Current value: 0 </span>
    <button> + </button>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const count = ref(0);
</script>