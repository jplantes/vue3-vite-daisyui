<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>

  <div class="flex justify-center">
    <button class="btn w-32" type="button" @click="count++">count is {{ count }}</button>
  </div>

</template>

<style scoped>

</style>
