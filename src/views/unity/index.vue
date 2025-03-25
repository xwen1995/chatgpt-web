<script setup lang="ts">
import UnityWebgl from 'unity-webgl'

const Unity = new UnityWebgl({
  loaderUrl: '/unity/中航锂电A9JFJK_50011.loader.js',
  dataUrl: '/unity/中航锂电A9JFJK_50011.data',
  frameworkUrl: '/unity/中航锂电A9JFJK_50011.framework.js',
  codeUrl: '/unity/中航锂电A9JFJK_50011.wasm',
})
</script>

<template>
  <div class="unity-container">
    <!-- <VueUnity :unity="Unity" ></VueUnity> -->
  </div>
</template>

<style scoped>
.unity-container {
  width: 100%;
  height: 100%;
}
</style>
