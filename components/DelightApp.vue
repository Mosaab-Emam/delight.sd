<script setup lang="ts">
const props = defineProps({
  name: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="w-12 h-12 .shadow shadow-amber">
    {{ props.name }}
  </div>
</template>
