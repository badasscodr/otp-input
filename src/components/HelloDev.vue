<script setup lang="ts">
const amiCoder = ref('Am I coder?') // ref is imported automatically
</script>

<template>
  <button class="btn">Hello Dev, {{ amiCoder }}?</button>
</template>
