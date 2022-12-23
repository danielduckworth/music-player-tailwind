<script setup lang="ts">
/* Code generated with AutoHTML Plugin for Figma */
import Spacer5 from './Spacer5.vue'
import TitleBar from './TitleBar.vue'
import Spacer6 from './Spacer6.vue'
import SongNavigation from './SongNavigation.vue'

// defineProps()
</script>

<template>
  <div
    class="bg-_2077-sys-light-surface rounded-[44px] flex flex-row gap-0 items-center justify-center w-[390px] h-[844px] relative overflow-hidden pt-0 pr-5 pb-0 pl-5"
    style="box-shadow: 0px 10px 40px -10px rgba(0, 0, 0, 0.25)"
  >
    <div class="flex flex-col gap-0 items-center justify-start flex-1 relative">
      <Spacer5 /><TitleBar title="Now playing" /><Spacer6 />
      <div
        class="bg-_2077-ref-neutral-variant-neutral-variant80 rounded-xl border self-stretch shrink-0 h-[370px] relative"
        style="
          border: solid var(--_2077-black, #000000);
          box-shadow: var(
            --elevation2-box-shadow,
            0px 2px 6px 2px rgba(0, 0, 0, 0.15),
            0px 1px 2px 0px rgba(0, 0, 0, 0.3)
          );
        "
      />
      <Spacer6 /><SongNavigation
        song-duration="4:02"
        artist="Artist"
        elapsed-time="2:25"
        song-name="Song Name"
      /><Spacer5 />
    </div>
  </div>
</template>

<style scoped></style>
