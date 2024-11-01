<script setup>
import { defineProps } from 'vue'

defineProps({
  placeholder: {
    type: String,
    default: 'Phone number',
  },
})
</script>

<template>
  <div class="flex py-0.5">
    <input
      class="border border-gray-300 focus:border-gray-400 w-full focus:outline-none px-2 py-2 text-sm placeholder:text-gray-500"
      type="text"
      :placeholder="placeholder"
    />
  </div>
</template>
