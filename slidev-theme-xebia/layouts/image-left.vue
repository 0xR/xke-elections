<script setup lang="ts">
import { computed } from "vue";
import { handleBackground } from "../utils/layoutHelper";

const props = defineProps<{
  background?: string;
  backgroundSize?: string;
  backgroundPosition?: string;
  backgroundRepeat?: string;
}>();

const style = computed(() =>
  handleBackground(props.background, {
    ...props,
  }),
);
</script>

<template>
  <div class="image-left">
    <div class="w-91.2 h-full absolute background-mask" :style="style" />
    <img src="../img/shapes/image-left.svg" class="absolute" />
    <SlideCurrentNo class="slidenumber" />
    <div class="slidev-layout">
      <slot />
    </div>
  </div>
</template>

<style lang="postcss">
.image-left {
  .slidev-layout {
    @apply pl-120;
  }

  .background-mask {
    mask-image: url(../img/masks/image-left-background.svg);
    mask-repeat: no-repeat;
  }
}
</style>
