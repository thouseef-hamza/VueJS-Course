<!-- Standard Way JS -> HTML -> CSS -->

<!-- JS -->
<script setup>
import NestedComponent from './NestedComponent.vue'
console.log('Hello World')
</script>

<!-- HTML -->
<template>
  <h1>This is a Parent Component</h1>
  <NestedComponent />
</template>

<!-- CSS -->
<style scoped>
h1 {
  color: red;
}
</style>
