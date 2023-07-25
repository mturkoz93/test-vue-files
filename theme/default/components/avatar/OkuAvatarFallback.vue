<script setup lang="ts">
import { OkuAvatarFallback } from '@oku-ui/avatar'
</script>

<template>
  <OkuAvatarFallback
    class="flex items-center text-white font-medium text-2xl h-full w-full justify-center"
    :delay-ms="100"
  >
    <slot />
  </OkuAvatarFallback>
</template>