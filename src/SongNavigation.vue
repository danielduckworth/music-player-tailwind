<script setup lang="ts">
/* Code generated with AutoHTML Plugin for Figma */
import IconThumbsUp from './IconThumbsUp.vue'
import Spacer6 from './Spacer6.vue'
import Progress from './Progress.vue'
import Spacer5 from './Spacer5.vue'
import IconRepeat from './IconRepeat.vue'
import IconSkipBack from './IconSkipBack.vue'
import PlayButton from './PlayButton.vue'
import IconSkipForward from './IconSkipForward.vue'
import IconShuffle from './IconShuffle.vue'

defineProps({
  songDuration: {
    type: [String, Boolean],
    default: '4:02',
  },
  artist: {
    type: [String, Boolean],
    default: 'Artist',
  },
  elapsedTime: {
    type: [String, Boolean],
    default: '2:25',
  },
  songName: {
    type: [String, Boolean],
    default: 'Song Name',
  },
})
</script>

<template>
  <div class="flex flex-col gap-0 items-center justify-start shrink-0 relative">
    <div
      class="flex flex-row items-center justify-between shrink-0 w-[350px] h-[54px] relative"
    >
      <div
        class="flex flex-col gap-1.5 items-start justify-start shrink-0 relative"
      >
        <div
          class="text-_2077-black text-left relative"
          style="
            font: var(--_2077-title-large, 700 22px/28px 'Inter', sans-serif);
          "
        >
          {{ songName }}
        </div>

        <div
          class="text-_2077-ref-neutral-variant-neutral-variant30 text-left relative"
          style="
            font: var(--_2077-body-large, 400 16px/24px 'Inter', sans-serif);
          "
        >
          {{ artist }}
        </div>
      </div>
      <IconThumbsUp />
    </div>
    <Spacer6 />
    <div
      class="flex flex-col gap-[17px] items-center justify-start shrink-0 w-[350px] h-9 relative"
    >
      <Progress />
      <div
        class="flex flex-row items-start justify-between self-stretch shrink-0 relative"
      >
        <div
          class="text-_2077-ref-neutral-variant-neutral-variant30 text-left relative"
          style="
            font: var(--_2077-label-medium, 500 12px/16px 'Inter', sans-serif);
          "
        >
          {{ elapsedTime }}
        </div>

        <div
          class="text-_2077-ref-neutral-variant-neutral-variant30 text-left relative"
          style="
            font: var(--_2077-label-medium, 500 12px/16px 'Inter', sans-serif);
          "
        >
          {{ songDuration }}
        </div>
      </div>
    </div>
    <Spacer5 />
    <div
      class="flex flex-row gap-6 items-center justify-center shrink-0 w-[350px] h-16 relative"
    >
      <IconRepeat /><IconSkipBack /><PlayButton /><IconSkipForward /><IconShuffle />
    </div>
  </div>
</template>

<style scoped></style>
