<script setup lang="ts">
/* Code generated with AutoHTML Plugin for Figma */
import BackButton from './BackButton.vue'
import MoreButton from './MoreButton.vue'

defineProps({
  title: {
    type: [String, Boolean],
    default: 'Now playing',
  },
})
</script>

<template>
  <div
    class="flex flex-row items-center justify-between self-stretch shrink-0 relative"
  >
    <BackButton />
    <div
      class="text-_2077-black text-left relative"
      style="font: var(--_2077-title-large, 700 22px/28px 'Inter', sans-serif)"
    >
      {{ title }}
    </div>
    <MoreButton />
  </div>
</template>

<style scoped></style>
