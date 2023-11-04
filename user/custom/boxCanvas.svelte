<script>
  import { Canvas } from '@threlte/core';
  import Scene from './boxScene.svelte';
</script>

<div class="canvas">
  <Canvas>
    <Scene />
  </Canvas>
</div>

<style scoped>
  div.canvas {
    height: 50vh;
    width: 100%;
  }
</style>
