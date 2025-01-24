<template>
  <router-view />
  <demo-counter />
</template>

<script setup>
import DemoCounter from "./demo1/DemoCounter.vue";
</script>

<style>
* {
  padding: 0;
  margin: 0;
  font-family: sans-serif;
}
</style>
