<script setup>
const myMessage = 'This is THOUSI World'
const myNumber = 101
function add(x, y) {
  return x + y
}
</script>

<template>
  <!-- Dynamic Data -->
  <div>
    <h1>This is from My Component with message of {{ myMessage }}</h1>
    <h2>{{ myNumber }}</h2>
    <h3>2 + 2 = {{ 2 + 2 }}</h3>
    <h4>Add Two Numbers {{ add(2, 8) }}</h4>
    <!-- <h5>Not Allowed {{ const name = "THousi" }}</h5> -->
  </div>
</template>
