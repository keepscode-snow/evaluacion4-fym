<template>
  <div class="calculator-display">
    {{ value }}
  </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  value: {
    type: String,
    required: true
  }
});
</script>

<style scoped>
.calculator-display {
  background: #222;
  color: #fff;
  font-size: 2em;
  padding: 0.5em;
  text-align: right;
}
</style>