<script setup lang="ts">
import { OkuAvatar } from '@oku-ui/avatar'


</script>

<template>
  <OkuAvatar :class="attrs.class ? attrs.class : "relative flex h-10 w-10 shrink-0 overflow-hidden rounded-full">
    <slot />
  </OkuAvatar>
</template>