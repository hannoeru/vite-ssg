<template>
  <p>Hello I am B</p>
  <img src="../assets/test.jpg" alt="">
</template>

<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Hello',
  meta: [
    {
      name: 'description',
      content: 'Website description',
    },
  ],
  style: [
    {
      children: 'body {color: #567839}',
    },
  ],
})
</script>
