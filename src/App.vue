<script setup>
import {ref} from 'vue'

const url = ref('https://dongxing.fun:31204')

window.open("https://dongxing.fun:31204")

</script>

<template>
  <iframe :src="url"></iframe>
</template>

<style scoped>
iframe {
  position: absolute;
  width: 100%;
  height: 100%;
  border: none;
}
</style>
