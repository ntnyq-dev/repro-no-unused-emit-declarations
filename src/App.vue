<script setup>
import VButton from './VButton.vue'

const handleClick = () => {
  console.log('clicked')
}
</script>

<template>
  <VButton @update="handleClick">Click me</VButton>
</template>
