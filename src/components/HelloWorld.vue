<script setup>
import { ref } from 'vue'
import { SignIn } from 'vue-clerk'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <SignIn/> 
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
