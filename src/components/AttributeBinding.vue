<script setup>
const myGIthubAc = 'https://github.com/thouseef-hamza';
const image = "https://cdn.pixabay.com/photo/2015/07/28/15/49/whirligig-864611_1280.jpg";
const altText = "Just a Picture";
const imageWidth=400;
const imageHeight=400;
</script>

<template>
  <!-- OLd Way -->
  <!-- <a v-bind:href="myGIthubAc" target="_blank">Thousi Github </a> -->

  <!-- New Way -->
  <a :href="myGIthubAc" target="_blank">Thousi Github </a>

  <!-- Image -->
  <img :src="image" :alt="altText" :width="imageWidth" :height="imageHeight" />
</template>
