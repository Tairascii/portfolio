<script setup lang="ts">
import { onMounted } from 'vue'

onMounted(() => {
  const wrapper = document.getElementById('textId')
  if (wrapper !== null) {
    window.addEventListener(
      'scroll',
      function () {
        const st = window.scrollY
        wrapper.style.transform = `translateX(${-1 * (st / 100)}%)`
      },
      { passive: true },
    )
  }
})
</script>
<script lang="ts">
export default {
  name: 'UpperSection',
}
</script>
<template>
  <div class="wrapper">
    <div class="background" />
    <div class="main">
      <div id="textId" class="text">
        <span v-for="item in [0, 1, 2]" :key="item" class="textMapper">
          <span>Software Engineer</span>
          <span>🚀</span>
          <span>Front-end </span>
          <span>🚀</span>
          <span>Back-end</span>
          <span>🚀</span>
        </span>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import './Divider.css';
</style>
