<script setup lang="ts">
import { NSplit } from 'naive-ui'
import { ref } from 'vue'
import chat from '../chat/index.vue'
import unity from '../unity/index.vue'

const split = ref(0.7)
</script>

<template>
  <NSplit v-model:size="split" direction="horizontal" class="w-full h-full" :max="0.75" :min="0.25">
    <template #1>
      <unity />
    </template>
    <template #2>
      <chat />
    </template>
  </NSplit>
</template>

<style>
</style>
