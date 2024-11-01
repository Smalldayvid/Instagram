<script setup>
import { defineProps } from 'vue'

defineProps({
  text: {
    type: String,
    default: 'Submit',
  },
})

const emit = defineEmits(['click'])

const handleClick = () => {
  emit('click')
}
</script>

<template>
  <button
    @click="handleClick"
    class="border-none rounded-md bg-sky-400 cursor-auto py-2 w-full text-white justify-items-center"
  >
    <slot />
  </button>
</template>
